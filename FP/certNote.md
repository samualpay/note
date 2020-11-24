一台機器至少要加入一個vpc一個vswitch
```
Terraform
1. 複製main.tf
2. 修改 main.tf
    * name_prefix
    * vswitch_ids
    * slb_name 
3. aliyun configure (需輸入 key and secret and region)
4. terraform init (初始化terraform)
5. terraform plan (check語法與修改地方)
6. terraform apply (Enter a value: yes)
7. 如需刪除 terraform destroy (Enter a value: yes)
8. 到ali istio 新增
    a. 選擇剛剛建立的集群
    b. 跟蹤採樣 100, 啟用服務就近訪問
    c. 攔截對外訪問的地址範圍 取消勾選‘全部’
    d. 勾選創建默認入口網關
        * 選擇公網
        * 使用已有負載均衡, 選取剛剛建立的的SLB
    e. 勾選‘啟用cert-manager管理證書’ 
    f. 勾選'啟用Prometheus度量日誌收集', 選擇‘新建Prometheus服務’
    g. Grafana & Kiali 密碼均為 !QAZ2wsx
    h. 啟用鏈入追蹤, 接入點地址為 華東2(上海)->HTTP->私網接入點
    i. 點選部署 istio
    j. 勾選'default', 點選‘啟用Sidecar自動注入’

```
terraform init
terraform plan


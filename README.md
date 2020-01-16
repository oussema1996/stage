# stage
#ENVIRONEMENT DE TRAVAIL 
docker 19.03.5
docker-compose 1.17.1
python 2.7.17
Odoo 12.0
PostgreSQL 
# Run Module 
cd stage
docker-compose up
Install Module Sales sale-management ( sale.order) 
Install Module Salesordersfamo
# NOTE 
If you have multiple bank accounts ( bank acount module ) the added field will be ( bank_account=fields.Many2one(
        name_of_your_bank_account_module',required=True))
You can change Sales module depending on your install module but don't forget to change Treeview,Formview and report externals ids



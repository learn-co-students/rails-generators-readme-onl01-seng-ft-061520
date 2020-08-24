

rails generate == rails g

Generate WITHOUT tests:
	rails generate <name of generator> <options> --no-test-framework

Rails Generator names:
	Migrations
	Models
	Controllers
	Resources

NOTE	Generator instructions: pre-pend add or remove & end-pend table name
		Generator instructions: column_name:string
rails g migration 	add_column_name_to_table				column_name:string 	--no-test-framework
rails g migration 	remove_column_name_from_table			column_name:string	--no-test-framework

rails g migration	add_column_name_to_table				column_name:boolean	--no-test-framework
rails g migration	change_column_name_data_type_to_table	column_name:string		--no-test-framework

rails g controller	admin dashboard stats financials settings	--no-test-framework

NOTE create, update, and destroy DON’T need erb files in views folder

resources :accounts 	<<= is considered a 'magic' route that entails the full set of RESTful routes needed to perform CRUD in an application

rake routes | grep account  	<<= filtered so it only shows the routes for accounts:




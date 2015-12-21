# sso-demo

To import demo-realm :

	standalone.sh -Dkeycloak.migration.action=import 
		-Dkeycloak.migration.provider=singleFile 
		-Dkeycloak.migration.file=demo-realm.json 
		-Dkeycloak.migration.realmName=demo-realm
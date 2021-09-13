# WebAppNetFrameworkSecurity
Web con seguridad

Tutorial de seguridad en .NET con VB.NET en .NET  Framework 4.8

Modificación a partir de web.config

Ejemplo de configuraciçon:

<?xml version="1.0" encoding="utf-8"?>
<configuration>

	<location path="AltaProducto">
		<system.web>
			<authorization>
				<deny users="?"/>
			</authorization>
		</system.web>
	</location>
	
  <system.web>
	
  </system.web>
</configuration>

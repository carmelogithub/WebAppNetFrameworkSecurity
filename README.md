# WebAppNetFrameworkSecurity
Configuración de seguridad con Autenticación y Autorización de usuarios

tutorial de seguridad en .NET con VB.NET en NET.FrameWork 4.8

Modificación a partir de web.config

Ejemplo de configuración para denegar acceso a usuarios NO registrados

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

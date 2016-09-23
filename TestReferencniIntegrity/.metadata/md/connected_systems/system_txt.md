<?xml version='1.0' encoding='UTF-8'?>
<system name="txt" elemId="7602">
	<description></description>
	<model>
		<relationships/>
		<tables>
			<table name="i_partner" elemId="8481">
				<description></description>
				<columns/>
			</table>
			<table name="rd_partner" elemId="8510">
				<description></description>
				<columns/>
			</table>
		</tables>
	</model>
	<sourceMappings>
		<mapping entity="partner_i" elemId="8681" table="i_partner" customOrigin="">
			<description></description>
		</mapping>
		<mapping entity="rd_ico" elemId="8682" table="rd_partner" customOrigin="">
			<description></description>
		</mapping>
	</sourceMappings>
	<loadOperations>
		<fullLoad nameSuffix="full" elemId="8452" allTables="false">
			<selectedTables>
				<table name="rd_ico" elemId="15116"/>
			</selectedTables>
			<advanced deletionStrategy="use global setting (from Preferences)">
				<ignoredComparisonColumns/>
				<pathVariables/>
				<additionalParameters/>
			</advanced>
		</fullLoad>
	</loadOperations>
</system>
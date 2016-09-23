<?xml version='1.0' encoding='UTF-8'?>
<system name="ref" elemId="5029">
	<description>referencni data</description>
	<model>
		<relationships/>
		<tables>
			<table name="rd_partner" elemId="5148">
				<description></description>
				<columns/>
			</table>
		</tables>
	</model>
	<sourceMappings>
		<mapping entity="rd_ico" elemId="5223" table="rd_partner" customOrigin="">
			<description></description>
		</mapping>
	</sourceMappings>
	<loadOperations>
		<fullLoad nameSuffix="full" elemId="5371" allTables="true">
			<selectedTables/>
			<advanced deletionStrategy="use global setting (from Preferences)">
				<ignoredComparisonColumns/>
				<pathVariables/>
				<additionalParameters/>
			</advanced>
		</fullLoad>
	</loadOperations>
</system>
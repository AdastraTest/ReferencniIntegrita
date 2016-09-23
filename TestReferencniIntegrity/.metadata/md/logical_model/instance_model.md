<?xml version='1.0' encoding='UTF-8'?>
<instanceModel>
	<relationships>
		<relationship parentRole="" name="new_relationship" elemId="6120" childRole="" type="Cross System" parentTable="rd_ico" childTable="partner_i">
			<description></description>
			<childToParent/>
			<parentToChild>
				<column source="src_jmeno" name="Jmeno" elemId="7430" type="string" size="200" createInto="master_partner_partner_merge">
					<filterExpression></filterExpression>
				</column>
				<column source="src_adresa" name="Adresa" elemId="7431" type="string" size="200" createInto="master_partner_partner_merge">
					<filterExpression></filterExpression>
				</column>
			</parentToChild>
			<advanced>
				<extendedSameSystem parentColumn="" enable="false" childColumn=""/>
				<alternativeKey alternativePk="" alternativeFk=""/>
			</advanced>
			<foreignKey>
				<column parentColumn="source_id" elemId="6155" childColumn="ico"/>
			</foreignKey>
		</relationship>
	</relationships>
	<tables>
		<table name="partner_i" elemId="7617" type="instance">
			<description></description>
			<columns>
				<column isPk="true" label="" isSco="false" type="string" size="200" isFk="false" refData="" isSrc="false" isExp="false" name="source_id" elemId="7693" isStd="false" isCio="false">
					<description></description>
				</column>
				<column isPk="false" label="" isSco="false" type="string" size="200" isFk="true" refData="" isSrc="false" isExp="false" name="ICO" elemId="4317" isStd="false" isCio="false">
					<description></description>
				</column>
				<column isPk="false" label="" isSco="false" type="string" size="200" isFk="false" refData="" isSrc="true" isExp="false" name="zisk" elemId="7694" isStd="true" isCio="true">
					<description></description>
				</column>
			</columns>
			<matchingTab enableIdentify="false" matching="true">
				<matchingTabColumns>
					<column name="mat_ico" elemId="5477" type="string" size="200">
						<description></description>
					</column>
				</matchingTabColumns>
				<multipleMatching disableDefault="false">
					<matchingDefinitions/>
				</multipleMatching>
			</matchingTab>
			<aggregationTab aggregation="false" groupingColumn="">
				<aggregationTabColumns/>
			</aggregationTab>
			<advanced>
				<specialColumns/>
				<historicalColumns/>
				<oldValueColumns/>
			</advanced>
		</table>
		<table name="rd_ico" elemId="7645" type="instance">
			<description></description>
			<columns>
				<column isPk="true" label="" isSco="false" type="string" size="200" isFk="false" refData="" isSrc="false" isExp="false" name="source_id" elemId="7832" isStd="false" isCio="false">
					<description></description>
				</column>
				<column isPk="false" label="" isSco="false" type="string" size="200" isFk="false" refData="" isSrc="true" isExp="false" name="jmeno" elemId="7833" isStd="true" isCio="true">
					<description></description>
				</column>
				<column isPk="false" label="" isSco="false" type="string" size="200" isFk="false" refData="" isSrc="true" isExp="false" name="adresa" elemId="7834" isStd="true" isCio="false">
					<description></description>
				</column>
			</columns>
			<matchingTab enableIdentify="false" matching="false">
				<matchingTabColumns/>
				<multipleMatching disableDefault="false">
					<matchingDefinitions/>
				</multipleMatching>
			</matchingTab>
			<aggregationTab aggregation="false" groupingColumn="">
				<aggregationTabColumns/>
			</aggregationTab>
			<advanced>
				<specialColumns/>
				<historicalColumns/>
				<oldValueColumns/>
			</advanced>
		</table>
	</tables>
	<dicTables/>
</instanceModel>
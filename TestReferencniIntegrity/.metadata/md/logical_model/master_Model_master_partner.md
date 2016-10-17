<?xml version='1.0' encoding='UTF-8'?>
<masterModel name="master_partner" elemId="7520">
	<description></description>
	<relationships/>
	<masterTables>
		<masterTable name="partner" elemId="11080" label="" entityRole="golden" instanceTable="partner_i" topLevel="true">
			<description></description>
			<columns>
				<column isCmo="false" refData="" isPk="true" isFk="false" description="" name="id" elemId="11188" label="" type="long_int" size=""/>
				<column isCmo="true" refData="" isPk="false" isFk="false" description="" name="ICO" elemId="11189" label="" type="string" size="200"/>
				<column isCmo="true" refData="" isPk="false" isFk="false" description="" name="zisk" elemId="11190" label="" type="string" size="200"/>
				<column isCmo="true" refData="" isPk="false" isFk="false" description="" name="Adresa" elemId="12829" label="" type="string" size="200"/>
				<column isCmo="true" refData="" isPk="false" isFk="false" description="" name="Jmeno" elemId="12830" label="" type="string" size="200"/>
			</columns>
			<guiTab>
				<reduceES allColumns="true">
					<reduceColumns/>
				</reduceES>
				<views/>
				<computedColumns/>
			</guiTab>
			<advanced groupColumn="" customActivity="false">
				<inputFilterExpression></inputFilterExpression>
				<specialColumns/>
			</advanced>
			<guiEdit guiReadOnly="use global setting (from GUI Configuration)">
				<editColumns/>
				<parentColumns/>
			</guiEdit>
		</masterTable>
	</masterTables>
	<instanceTables/>
	<guiConfig enableGui="false" guiSystem="mda" guiMode="Read-Only">
		<hierarchies/>
		<actions hierarchies="true" revert="false" manualExceptions="true" edit="false" deactivate="false" create="false"/>
		<indicators dqi="true"/>
		<batchOperations guiInitialLoad="false" guiFullLoad="false" guiLoadAllEntities="true">
			<loadedEntities/>
		</batchOperations>
	</guiConfig>
</masterModel>
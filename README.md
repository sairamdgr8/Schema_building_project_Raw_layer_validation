# Schema_building_project_Raw_layer_validation
Raw_layer_validation

1) it checks the number of columns ,column name and column datatype are matching with the source schema to metaschema.
2) if column count doent matches then the code will fail to write the job to the target location.


Note:here MetaSchema is a json file which consists of column name and and its dataype defined by you inorder to validate with the respective source file schema

@AbapCatalog.viewEnhancementCategory: [#NONE]
@AccessControl.authorizationCheck: #CHECK
@EndUserText.label: 'Gender'
@Metadata.ignorePropagatedAnnotations: true
@ObjectModel.resultSet.sizeCategory: #XS
@Search.searchable: true
define view entity ZI_Gender as select from zgender {
    @UI.hidden: true
    key gender_uuid as GenderUuid,
    @Search.defaultSearchElement: true
    gender as Gender
}

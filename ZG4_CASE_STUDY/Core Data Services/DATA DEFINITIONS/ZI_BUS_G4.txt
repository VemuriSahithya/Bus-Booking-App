@AccessControl.authorizationCheck: #CHECK
@EndUserText.label: 'Homepage'
define root view entity ZI_BUS_G4 as select from zbus_g4
{
    @UI.hidden: true
    key bus_uuid as BusUuid,
    bus_id as BusId,
    bus_name as BusName,
    source as Source,
    destination as Destination,
    fare as Fare,
    total_seats as TotalSeats,
    departure_time as DepartureTime,
    duration as Duration,
    @UI.hidden: true
    last_changed_at as LastChangedAt,
    @UI.hidden: true
    local_last_changed_at as LocalLastChangedAt

}

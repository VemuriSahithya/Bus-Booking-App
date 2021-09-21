# Bus-Booking-App

1) Make all classes(except ZC_INSERT_DATA and ZCM_Message_G4) using quickfix in behaviour definition only.
   Don't make them manually. 
   This is because all the code in classes files are to be pasted in the local classes created by quickfix.

2) Please note the latest data types to be used during all domain creations:
	a)ZD_CUR_STATUS : CHAR(25).
	b)ZD_BOOKING_DATUM : DATS(8).
	c)ZD_BUS_ID_INT: INT8.
	d)ZD_GENDER_VALUES: CHAR(20).
	e)ZD_BUS_NAME_: CHAR(25).
	f)ZD_BUSIDE: CHAR (25).
	g)ZD_DEPARTURE_TIME: TIMS.
	h)ZD_DEST: CHAR(25).
	i)ZD_DURATION: INT8.
	j)ZD_EMPTY_SEATS: INT8.
	k)ZD_FARE_: INT8.
	l)ZD_PASS_NAME: CHAR(25).
	m)ZD_PASSENGER_AGE: INT1.
	n)ZD_PHONE: CHAR(10).
	o)ZD_PNR_ID_INT: INT8.
	p)ZD_PNR_: CHAR(25).
	q)ZD_ROW_NUMBER:INT1.
	r)ZD_SRC: CHAR(25).
	s)ZD_START_DATE: DATS.
	t)ZD_TOTAL_SEATS: INT8.
	u)ZD_TRAVEL_ID_INT: INT8.
	v)ZD_TRAVELIDE: CHAR(25).
	w)ZD_USERIDE: CHAR(25).

3) Please insert data manually in ZGENDER and ZVALUE table before using anything. You can use our test class ZC_INSERT_DATA for the same. Check the screenshot of Data preview for both of them in root folder of project.

4) Create message(Z_MESSAGE_G4) and exception(ZCM_MESSAGE_G4) by right clicking on the package name. 

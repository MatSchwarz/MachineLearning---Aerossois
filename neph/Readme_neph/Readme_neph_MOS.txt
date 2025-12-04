Global attributes:
	File: neph
	Instrument: Nephelometer
	Model: TSI 3563
	Additional_instruments: n/a
	Station_ID: MOS
	Location: Arctic Ocean (MOSAiC)
	Site_type: Polar/Marine
	Station_Latitude: variable (see locations related data set: MOS_location_[avgt].csv)
	Station_Longitude: variable (see locations related data set: MOS_location_[avgt].csv)
	Station_Altitude: 12 masl
	Time_Coordinate: UTC
	Time_Stamp_Info: yyyy-mm-dd hh:mm:ss
	Time_resolution: 5-min/1-h
	Data_Info: Aerosol scattering and backscattering coefficients reported at 450, 550 and 700 nm. Truncation corrected - 
		see description in related data paper. Generated from DOE file: mosaosnephdry1mM1.b1.[timestamp].nc
	Uncertainty: 10%. Depends on particle size, loading and averaging period. See Table 5 in related data paper.
	pT_Conditions: Standard temperature and pressure (STP, Tstd = 0 degC and Pstd= 1013 hPa).
	Data_Contact: betsy.andrews@noaa.gov


Variables:	
	Start_date
		missing_val: NaN
		short_name: Date
		long_name: Start date in UTC (yyyy-mm-dd hh:mm:ss format)
		units:
	BsB10_STP  
		missing_val: NaN
		short_name: BsB10_STP  
		long_name: Scattering coefficient for 450 nm at STP, PM10 size cut
		units: Mm-1
	BsG10_STP 
		missing_val: NaN
		short_name: BsG10_STP
		long_name: Scattering coefficient for 550 nm at STP, PM10 size cut
		units: Mm-1
	BsR10_STP
		missing_val: NaN
		short_name: BsR10_STP
		long_name: Scattering coefficient for 700 nm at STP, PM10 size cut
		units: Mm-1
	BbsB10_STP
		missing_val: NaN
		short_name: BbsB10_STP
		long_name:  Backscattering coefficient for 450 nm at STP, PM10 size cut
		units: Mm-1
	BbsG10_STP
		missing_val: NaN
		short_name: BbsG10_STP
		long_name: Backscattering coefficient for 550 nm at STP, PM10 size cut
		units: Mm-1
	BbsR10_STP
		missing_val: NaN
		short_name: BbsR10_STP
		long_name: Backscattering coefficient for 700 nm at STP, PM10 size cut
		units: Mm-1
	T_neph_inlet10
		missing_val: NaN
		short_name: T_neph_inlet10
		long_name: Nephelometer inlet temperature for PM10 size cut
		units: oC
	RH_neph10 
		missing_val: NaN
		short_name: RH_neph10
		long_name: Nephelometer sample RH for PM10 size cut
		units: %
	T_neph10
		missing_val: NaN
		short_name T_neph10
		long_name: Nephelometer sample temperature for PM10 size cut
		units: oC
	P_neph10
		missing_val: NaN
		short_name: P_neph10
		long_name: Nephelometer sample pressure for PM10 size cut
		units: hPa
	BsB1_STP
		missing_val: NaN
		short_name: BsB1_STP
		long_name: Scattering coefficient for 450 nm at STP, PM1 size cut				units: Mm-1
	BsG1_STP 
		missing_val: NaN
		short_name: BsG1_STP 
		long_name: Scattering coefficient for 550 nm at STP, PM1 size cut
		units: Mm-1
	BsR1_STP 
		missing_val: NaN
		short_name: BsR1_STP
		long_name: Scattering coefficient for 700 nm at STP, PM1 size cut
		units: Mm-1
	BbsB1_STP 
		missing_val: NaN
		short_name: BbsB1_STP
		long_name: Backscattering coefficient for 450 nm at STP, PM1 size cut
		units: Mm-1
	BbsG1_STP
		missing_val: NaN
		short_name: BbsG1_STP
		long_name: Backscattering coefficient for 550 nm at STP, PM1 size cut
		units: Mm-1
	BbsR1_STP 
		missing_val: NaN
		short_name: BbsR1_STP 
		long_name: Backscattering coefficient for 700 nm at STP, PM1 size cut
		units: Mm-1
	T_neph_inlet1
		missing_val: NaN
		short_name: T_neph_inlet1
		long_name: Nephelometer inlet temperature for PM1 size cut
		units: oC
	RH_neph1
		missing_val: NaN
		short_name: RH_neph1
		long_name: Nephelometer sample RH for PM1 size cut
		units: %
	T_neph1 
		missing_val: NaN
		short_name: T_neph1
		long_name: Nephelometer sample temperature for PM1 size cut
		units: oC
	P_neph1
		missing_val: NaN
		short_name: P_neph1
		long_name: Nephelometer sample pressure for PM1 size cut
		units: hPa
	num_pts10
		missing_val: NaN
		short_name: num_pts10
		long_name: Number of points in PM10 average
		units:
	num_pts1
		missing_val: NaN
		short_name: num_pts1
		long_name: Number of points in PM1 average
		units:

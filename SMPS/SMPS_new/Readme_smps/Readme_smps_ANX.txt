Global attributes:
	File: smps
	Instrument: Scanning mobility particle sizer (SMPS)
	Model: TSI 3938
	Classifier: 3082
	Detector: 3750
	Delay_time: 1.53 s
	Sample_flow: 1 lpm
	Channels_per_decade: 64
	Size_range (min-max): 10/11-496/514 nm
	Additional_instruments: Condensation Particle Counter; Nephelometer; Aerosol Chemical Speciation Monitor
	Station_ID: ANX
	Location: Andenes, Norway (COMBLE)
	Site_type: Polar/Marine
	Station_Latitude: 69.14 N
	Station_Longitude: 15.68 E
	Station_Altitude: 2 masl
	Time_Coordinate: UTC
	Time_Stamp_Info: yyyy-mm-dd hh:mm:ss
	Time_resolution: 5-min/1-h
	Data_Info: Particle number size distribution. Generated from DOE file:	anxaossmpsM1.b1.[timestamp].nc
	Uncertainty: 10-15%. Depends on flow rate and charging efficiency. See Table 5 in related data paper.
	pT_Conditions: Standard temperature and pressure (STP, Tstd = 0 degC and Pstd= 1013 hPa)
	Data_Contact: ineszabala@ugr.es


Variables:
	Start_date 
		missing_val: NaN
		short_name: Start_date
		long_name: Start date in UTC (yyyy-mm-dd hh:mm:ss format).
		units:
	N_CN_SMPS_STP
		missing_val: NaN
		short_name: N_CN_SMPS_STP 
		long_name: Total particle number concentration from SMPS at STP (see P_SMPS, T_SMPS).
		units: cm-3
	P_SMPS
		missing_val: NaN
		short_name: P_SMPS
		long_name: Sample pressure from SMPS.
		units: hPa
	T_SMPS
		missing_val: NaN
		short_name: T_SMPS
		long_name: Sample temperature from SMPS.
		units:  degC
	RH_SMPS
		missing_val: NaN
		short_name: RH_SMPS
		long_name: Sample relative humidity from SMPS.
		units: %
	N_CN_CPC_STP
		missing_val: NaN
		short_name: N_CN_CPC_STP
		long_name: Total particle concentration from CPC at STP.
		units: cm-3
	Qc_CPC_SMPS
		missing_val: NaN
		short_name: Qc_SMPS_CPC
		long_name: Quality check of number closure. Flag indicates comparison of N_CN_SMPS_STP and N_CN_SMPS_STP. Qc=0 differences smaller than 50%; Qc=1 differences bigger than 50%.		
		units: 
	Qc_ACSM_SMPS
		missing_val: NaN
		short_name: Qc_ACSM_SMPS
		long_name: Quality check of PM1 mass closure. Flag indicates comparison of Mass_ACSM_PSAP_STP and Mass_SMPS_STP. Qc= 0 for differences smaller than 50%; Qc = 1 for differences bigger than 50%.		
		units: 
	Qc_Neph_SMPS 
		missing_val: NaN
		short_name: Qc_Neph_SMPS
		long_name: Quality check of scattering closure. lag indicates comparison of calculated aerosol scattering coefficient and BsG1_STP measured by the integrating nephelometer. Qc=0 differences smaller than 50%; Qc=1 differences bigger than 50%.
		units: 
	dNi/dlogDi (bin1, bin2,…,bin113)
		missing_val: NaN
		short_name: dNi/dlogDi
		long_name: Particle number size concentration at STP for each size bin (Midpoint diameter for each size bin is given in header for each dNi/dlogDi column).
		units: cm-3


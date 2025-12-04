Global attributes:
	File: acsm
	Instrument: Aerosol Chemical Speciation Monitor (ACSM)
	Model: Q-ACSM
	Additional_instruments: Scanning Mobility Particle Sizer
	Station_ID: SGP
	Location: Oklahoma, USA (Southern Great Plains)
	Site_type: Continental
	Station_Latitude: 36.61 N
	Station_Longitude: 97.49 W
	Station_Altitude: 318 masl
	Time_Coordinate: UTC
	Time_Stamp_Info: yyyy-mm-dd hh:mm:ss
	Time_resolution: 1-h
	Data_Info: Aerosol chemical composition. Generated from DOE file: sgpacsmcdceE13.c2.[timestamp].nc
	Uncertainty: 9-10 % total mass concentration and 10-40 % species concentration (depends on species). See Table 5 in related data paper.
	pT_Conditions: Standard temperature and pressure (STP, Tstd = 0 degC and Pstd= 1013 hPa)
	Data_Contact: u1375376@utah.edu


Variables:
	Start_date 
		missing_val: NaN
		short_name: Start_date
		long_name: Start date in UTC (yyyy-mm-dd hh:mm:ss format).
		units:	
	Mass_organics_STP 
		missing_val: NaN
		short_name: Mass_organics_STP
		long_name: Mass concentration of particle organics at STP.					
		units: μg/m³
	Mass_sulfate_STP 
		missing_val: NaN
		short_name: Mass_sulfate_STP
		long_name: Mass concentration of particle sulfate at STP.					
		units: μg/m³
	Mass_ammonium_STP 
		missing_val: NaN
		short_name: Mass_ammonium_STP
		long_name: Mass concentration of particle ammonium at STP.					
		units: μg/m³
	Mass_nitrate_STP 
		missing_val: NaN
		short_name: Mass_nitrate_STP
		long_name: Mass concentration of particle nitrate at STP.					
		units: μg/m³
	Mass_chloride_STP 
		missing_val: NaN
		short_name: Mass_chloride_STP
		long_name: Mass concentration of particle chloride at STP.					
		units: μg/m³
	Mass_ACSM_STP
		missing_val: NaN
		short_name: Mass_ACSM_STP
		long_name: Mass concentration from ACSM at STP.
		units: μg/m³
	Mass_SMPS_STP
		missing_val: NaN
		short_name: Mass_SMPS_STP 
		long_name: Mass concentration from SMPS at STP.
		units: μg/m³
	Mass_BC_PSAP_STP
		missing_val: NaN
		short_name: Mass_BC_PSAP_STP 
		long_name: Mass concentration of black carbon calculated from PSAP absorption coefficient using green wavelength (529 nm) and PM1 size cut at STP.
		units: μg/m³
	Mass_ACSM_PSAP_STP
		missing_val: NaN
		short_name: Mass_ACSM_PSAP_STP 
		long_name: Sum of mass concentration from ACSM and PSAP at STP.
		units: μg/m³
	Qc_ACSM_SMPS
		missing_val: NaN
		short_name: Qc_ACSM_SMPS
		long_name: Quality check of PM1 mass closure. Flag indicates comparison of Mass_ACSM_PSAP_STP and Mass_SMPS_STP. Qc = 0 for differences smaller than 50%; Qc = 1 for differences bigger than 50%.
		units:
	P_SMPS
		missing_val: NaN
		short_name: P_SMPS
		long_name: Sample pressure from SMPS.
		units: hPa
	T_SMPS
		missing_val: NaN
		short_name: T_SMPS
		long_name: Sample temperature from SMPS.
		units: degC
	RH_SMPS 
		missing_val: NaN
		short_name: RH_SMPS 
		long_name: Sample relative humidity from SMPS.
		units: %

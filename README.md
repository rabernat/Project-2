# Scientific Question / Hypothesis
What are the daily atmospheric circulation regimes for North America? Do they match the Weather Types found by N. Vigaud and A.W. Robertson, 2018? They should match, if we choose months between October and March as stated in the paper. 

We use in our case geopotential height anomalies as climate predictor. 

# Links to the Scientific Datasets
To see the original source of the data, see the following URLs below for model and reanalysis data: 
model_url_Oct3rd_2019=https://iridl.ldeo.columbia.edu/SOURCES/.ECMWF/.S2S/.ECMF/.reforecast/.perturbed/.pressure_level_gh/.gh/P/500/VALUE/P/removeGRID/S/(3%20Oct%202019)/VALUE/X/(-170)/(-30)/RANGE/Y/(20)/(80)/RANGE/hdate/(1999)/(2018)/RANGE/L/5/runningAverage/dup/%5Bhdate/M%5D/average/sub/S/removeGRID/data.nc

model_url_Dec5th_2019=https://iridl.ldeo.columbia.edu/SOURCES/.ECMWF/.S2S/.ECMF/.reforecast/.perturbed/.pressure_level_gh/.gh/P/500/VALUE/P/removeGRID/S/(5%20Dec%202019)/VALUE/X/(-170)/(-30)/RANGE/Y/(20)/(80)/RANGE/hdate/(1999)/(2018)/RANGE/L/5/runningAverage/dup/%5Bhdate/M%5D/average/sub/S/removeGRID/data.nc 

reanalysis_url_Oct3rd_2019=https://iridl.ldeo.columbia.edu/auth/login?ver=1&redirect=%2FSOURCES%2F.ECMWF%2F.S2S%2F.ECMF%2F.reforecast%2F.perturbed%2F.pressure_level_gh%2F.gh%2FP%2F500%2FVALUE%2FP%2FremoveGRID%2FS%2F%283%20Oct%202019%29%2FVALUE%2FX%2F%28-170%29%2F%28-30%29%2FRANGE%2FY%2F%2820%29%2F%2880%29%2FRANGE%2Fhdate%2F%281999%29%2F%282018%29%2FRANGE%2Fhdate%2F%2Fpointwidth%2F0%2Fdef%2F-6%2FshiftGRID%2Fhdate%2F%28days%20since%201960-01-01%29%2Fstreamgridunitconvert%2FS%2F%28days%20since%202018-01-01%29%2Fstreamgridunitconvert%2FS%2F%2Funits%2F%2Fdays%2Fdef%2FL%2F0.5%2Fadd%2Fhdate%2Fadd%2Fadd%2F%2Fpointwidth%2F1%2Fdef%2FSOURCES%2F.ECMWF%2F.ERA-Interim%2F.SIX-HOURLY%2F.pressure_level%2F.z500%2FT%2F3%2FshiftGRID%2FT%2F24%2FboxAverage%2FT%2F2%2Findex%2F.units%2Fstreamgridunitconvert%2Fexch%2F%5BT%5Dsample-along%2Fc%3A%2F9.81%2F%28m%20s-2%29%2F%3Ac%2Fdiv%2FS%2FremoveGRID%2FL%2F5%2FrunningAverage%2F%5BX%2FY%5D%2F1.0%2F0.%2FregridLinear%2Fdup%2F%5Bhdate%5Daverage%2F2%2FRECHUNK%2Fsub%2Fdata.nc&realm=iri.columbia.edu%2Fterms%2Fs2s%2F1 

reanalysis_url_Dec5th_2019=https://iridl.ldeo.columbia.edu/auth/login?ver=1&redirect=%2FSOURCES%2F.ECMWF%2F.S2S%2F.ECMF%2F.reforecast%2F.perturbed%2F.pressure_level_gh%2F.gh%2FP%2F500%2FVALUE%2FP%2FremoveGRID%2FS%2F%285%20Dec%202019%29%2FVALUE%2FX%2F%28-170%29%2F%28-30%29%2FRANGE%2FY%2F%2820%29%2F%2880%29%2FRANGE%2Fhdate%2F%281999%29%2F%282018%29%2FRANGE%2Fhdate%2F%2Fpointwidth%2F0%2Fdef%2F-6%2FshiftGRID%2Fhdate%2F%28days%20since%201960-01-01%29%2Fstreamgridunitconvert%2FS%2F%28days%20since%202018-01-01%29%2Fstreamgridunitconvert%2FS%2F%2Funits%2F%2Fdays%2Fdef%2FL%2F0.5%2Fadd%2Fhdate%2Fadd%2Fadd%2F%2Fpointwidth%2F1%2Fdef%2FSOURCES%2F.ECMWF%2F.ERA-Interim%2F.SIX-HOURLY%2F.pressure_level%2F.z500%2FT%2F3%2FshiftGRID%2FT%2F24%2FboxAverage%2FT%2F2%2Findex%2F.units%2Fstreamgridunitconvert%2Fexch%2F%5BT%5Dsample-along%2Fc%3A%2F9.81%2F%28m%20s-2%29%2F%3Ac%2Fdiv%2FS%2FremoveGRID%2FL%2F5%2FrunningAverage%2F%5BX%2FY%5D%2F1.0%2F0.%2FregridLinear%2Fdup%2F%5Bhdate%5Daverage%2F2%2FRECHUNK%2Fsub%2Fdata.nc&realm=iri.columbia.edu%2Fterms%2Fs2s%2F1

Follow instructions for a double login.

Login IRI username: pr2616@columbia.edu

Login IRI password: Patric1234

Save the data into the folder with name 'data' which we created just above.

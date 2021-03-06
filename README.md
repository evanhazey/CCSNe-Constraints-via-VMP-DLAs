# CCSNe-Constraints-via-VMP-DLAs
Data used in the VMP DLA Paper (arxiv:2108.00659}

*_full.fits: Contains all measurements for a given system. Will not be hosted through the journal (i.e., only available here)

*_analysis.fits: Contains only the abundance measurements used in our analysis (i.e., no duplicates). Will be available in the journal (accepted December 2021).


## FITS Columns ##

**QSO**: Name of the quasar that the DLA is pointed towards. The numbers refer to the right ascension and declination of the quasar (and hence, the DLA)

**QSOFullName**: SIMBAD/NED compatible name of quasar

**z_abs**: Redshift of the DLA

**logNH**: Log base 10 of the hydrogen column density (# atoms/square centimeter)

**e_logNH**: Logarithmic error in the measurement of log(NH)

**l_[X/H]**: Limit of [X/H] measurement; '=' is normal, '<' is upper limit, and 'x' means there is no measurement 

**[X/H]**: Measurement of [X/H] (normalized to Asplund+2009 solar scale)

**e_[X/H]**: Error (+/-) in the [X/H] measurement; if l_[X/H] == '<' or 'x' then there is no e_[X/H]

**Instrument**: Instrument(s) used to obtain spectra/measure abundance

**Ref**: Reference(s) code number (see 'Reference Codes' below)


### Reference Codes ###

1: Lu et al. (1996)

2: Prochaska & Wolfe (1997a)

3: Prochaska & Wolfe (1999)

4: Molaro et al. (2000)

5: Prochaska & Wolfe (2000)

6: Dessauges-Zavadsky et al. (2001)

7: Molaro et al. (2001)

8: Prochaska et al. (2001)

9: Prochaska et al. (2001a)

10: Prochaska et al. (2002a)

11: Dessauges-Zavadsky et al. (2003)

12: Ledoux et al. (2003)

13: Prochaska et al. (2003c)

14: Prochaska et al. (2003a)

15: O'Meara et al. (2006)

16: Noterdaeme et al. (2007)

17: Prochaska et al. (2007)

18: Noterdaeme et al. (2008)

19: Petitjean, Ledoux & Srianand (2008)

20: Pettini et al. (2008)

21: Ellison et al. (2010)

22: Penprase et al. (2010)

23: Srianand et al. (2010)

24: Balashev et al. (2011)

25: Cooke et al. (2011)

26: Cooke et al. (2011b)

27: Cooke et al. (2012)

28: Cooke et al. (2014)

29: Dutta et al. (2014)

30: Zafar et al. (2014d)

31: Cooke et al. (2015)

32: Cooke et al. (2016)

33: Morrison et al. (2016)

34: Cooke et al. (2017)

35: D'Ordorico et al. (2018)

36: Welsh et al. (2019)

37: Welsh et al. (2020)

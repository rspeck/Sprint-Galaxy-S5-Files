# Sprint-Galaxy-S5-Files

Fresh from Sprint store - new SIM, LTE working

Model number:     SM-G900P
Android version:  6.0.1
Baseband version: G900PVPS3CQB3
Build number:     MMB29M.G900PVPS3CQB3

Settings:
  Network mode - Preferred network mode:  LTE/CDMA
  Access Point Names #greyed, immutable on stock#
    APN0 EHRPD ota (otasn)
    APN0 LTE ota (otasn)
    APN2 EHRPD internet (n.ispsn)
    APN2 LTE internet (n.ispsn)     
    Global Roaming - SPRINT (cinet.spcs)

telephony.db copied after root with CF-Auto-Root
  Note table 'siminfo' column 'icc_id' has been zero'd out by me.  
  Of the two entries, entry _id=2 has value for 'icc_id' equal to the ICCID found in Aboutdevice->Status->ICCID
  Entry _id=1 may be my old sim info - not sure.
  The apns listed in Access Point Names in Settings all have MCC=310 and MNC=120 which is what the siminfo entry has as well

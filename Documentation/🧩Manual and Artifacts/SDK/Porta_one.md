# Porta_one — Distortion

← [SDK](../SDK.md)

**Audio Precision** — Audio Precision Portable One Plus / Dual Domain audio analyzer

| | |
|---|---|
| Channels |  |
| HTTP | `:15901/api/instrument/Distortion/Porta_one` |
| `spec` | `/api/instrument/Distortion/Porta_one/Porta_one.api.json` |
| `health` | `/api/instrument/Distortion/Porta_one/health` |
| `get` | `/api/instrument/Distortion/Porta_one/get/<command>` |
| `set` | `/api/instrument/Distortion/Porta_one/set/<command>` |
| `nab` | `/api/instrument/Distortion/Porta_one/nab/<command>` |
| `rig` | `/api/instrument/Distortion/Porta_one/rig/<command>` |
| `do` | `/api/instrument/Distortion/Porta_one/do/<command>` |
| socket `ws` | `/ws/instrument/Distortion/Porta_one` |
| socket `readings` | `/ws/instrument/Distortion/Porta_one/readings` |
| socket `unix` | `/run/apk/instruments/Distortion.Porta_one.sock` |
| Reference | [commands tree](../../../Porta_one/commands_tree.md) · [sources](../../../Porta_one/SOURCES.md) |

## `get` — reads one value (288)

| Command | SCPI | Argument | Group | |
|---|---|---|---|---|
| `Get_Acm_Lun` | `ACMains:LUNit?` |  | ACM | unverified |
| `Get_Acm_Mmax` | `ACMains:MMAX?` |  | ACM | unverified |
| `Get_Acm_Mmin` | `ACMains:MMIN?` |  | ACM | unverified |
| `Get_Acm_Unit` | `ACMains:UNIT?` |  | ACM | unverified |
| `Get_Ampl_Amax` | `AMPLitude:AMAX?` |  | AMPL | unverified |
| `Get_Ampl_Amin` | `AMPLitude:AMIN?` |  | AMPL | unverified |
| `Get_Ampl_Bpfr` | `AMPLitude:BPFR?` |  | AMPL | unverified |
| `Get_Ampl_Ext` | `AMPLitude:EXTernal?` |  | AMPL | unverified |
| `Get_Ampl_Filt` | `AMPLitude:FILTer?` |  | AMPL | unverified |
| `Get_Ampl_Fmax` | `AMPLitude:FMAX?` |  | AMPL | unverified |
| `Get_Ampl_Fmin` | `AMPLitude:FMIN?` |  | AMPL | unverified |
| `Get_Ampl_Hpas` | `AMPLitude:HPASs?` |  | AMPL | unverified |
| `Get_Ampl_Lpas` | `AMPLitude:LPASs?` |  | AMPL | unverified |
| `Get_Ampl_Mmax` | `AMPLitude:MMAX?` |  | AMPL | unverified |
| `Get_Ampl_Mmin` | `AMPLitude:MMIN?` |  | AMPL | unverified |
| `Get_Ampl_Spe` | `AMPLitude:SPEed?` |  | AMPL | unverified |
| `Get_Ampl_Steps` | `AMPLitude:STEPS?` |  | AMPL | unverified |
| `Get_Ampl_Swpt` | `AMPLitude:SWPType?` |  | AMPL | unverified |
| `Get_Ampl_Unit` | `AMPLitude:UNIT?` |  | AMPL | unverified |
| `Get_Ampl_Wtd` | `AMPLitude:WTD?` |  | AMPL | unverified |
| `Get_Damp_Amax` | `DAMPlitude:AMAX?` |  | DAMP | unverified |
| `Get_Damp_Amin` | `DAMPlitude:AMIN?` |  | DAMP | unverified |
| `Get_Damp_Bpfr` | `DAMPlitude:BPFR?` |  | DAMP | unverified |
| `Get_Damp_Ext` | `DAMPlitude:EXTernal?` |  | DAMP | unverified |
| `Get_Damp_Filt` | `DAMPlitude:FILTer?` |  | DAMP | unverified |
| `Get_Damp_Fmax` | `DAMPlitude:FMAX?` |  | DAMP | unverified |
| `Get_Damp_Fmin` | `DAMPlitude:FMIN?` |  | DAMP | unverified |
| `Get_Damp_Hpas` | `DAMPlitude:HPASs?` |  | DAMP | unverified |
| `Get_Damp_Lpas` | `DAMPlitude:LPASs?` |  | DAMP | unverified |
| `Get_Damp_Mmax` | `DAMPlitude:MMAX?` |  | DAMP | unverified |
| `Get_Damp_Mmin` | `DAMPlitude:MMIN?` |  | DAMP | unverified |
| `Get_Damp_Spe` | `DAMPlitude:SPEed?` |  | DAMP | unverified |
| `Get_Damp_Step` | `DAMPlitude:STEPs?` |  | DAMP | unverified |
| `Get_Damp_Swpt` | `DAMPlitude:SWPType?` |  | DAMP | unverified |
| `Get_Damp_Unit` | `DAMPlitude:UNIT?` |  | DAMP | unverified |
| `Get_Damp_Wtd` | `DAMPlitude:WTD?` |  | DAMP | unverified |
| `Get_Dchk_Bits` | `DCHK:BITS?` |  | DCHK | unverified |
| `Get_Dchk_Dbit` | `DCHK:DBITs?` |  | DCHK | unverified |
| `Get_Dchk_Dun` | `DCHK:DUNit?` |  | DCHK | unverified |
| `Get_Dchk_Mmax` | `DCHK:MMAX?` |  | DCHK | unverified |
| `Get_Dchk_Mmin` | `DCHK:MMIN?` |  | DCHK | unverified |
| `Get_Dchk_Unit` | `DCHK:UNIT?` |  | DCHK | unverified |
| `Get_Dimd_Amax` | `DIMD:AMAX?` |  | DIMD | unverified |
| `Get_Dimd_Amin` | `DIMD:AMIN?` |  | DIMD | unverified |
| `Get_Dimd_Lun` | `DIMD:LUNit?` |  | DIMD | unverified |
| `Get_Dimd_Mmax` | `DIMD:MMAX?` |  | DIMD | unverified |
| `Get_Dimd_Mmin` | `DIMD:MMIN?` |  | DIMD | unverified |
| `Get_Dimd_Spe` | `DIMD:SPEed?` |  | DIMD | unverified |
| `Get_Dimd_Step` | `DIMD:STEPs?` |  | DIMD | unverified |
| `Get_Dimd_Unit` | `DIMD:UNIT?` |  | DIMD | unverified |
| `Get_Dio_Ddref` | `DIO:DDREF?` |  | DIO | unverified |
| `Get_Dio_Dir` | `DIO:DIResolution?` |  | DIO | unverified |
| `Get_Dio_Dref` | `DIO:DREF?` |  | DIO | unverified |
| `Get_Dio_Dun` | `DIO:DUNit?` |  | DIO | unverified |
| `Get_Dio_Frqr` | `DIO:FRQRef?` |  | DIO | unverified |
| `Get_Dio_Mmax` | `DIO:MMAX?` |  | DIO | unverified |
| `Get_Dio_Mmin` | `DIO:MMIN?` |  | DIO | unverified |
| `Get_Dio_Unit` | `DIO:UNIT?` |  | DIO | unverified |
| `Get_Dist_Cod` | `DISTatus:CODing?` |  | DIST | unverified |
| `Get_Dist_Con` | `DISTatus:CONfidence?` |  | DIST | unverified |
| `Get_Dist_Err` | `DISTatus:ERRor?` |  | DIST | unverified |
| `Get_Dist_Inv` | `DISTatus:INValid?` |  | DIST | unverified |
| `Get_Dist_Lock` | `DISTatus:LOCK?` |  | DIST | unverified |
| `Get_Dist_Par` | `DISTatus:PARity?` |  | DIST | unverified |
| `Get_Dist_Stat` | `DISTatus:STATus?` |  | DIST | unverified |
| `Get_Dist_Std` | `:DISTatus:STD?` |  | DIST | unverified |
| `Get_Djit_Amax` | `DJITter:AMAX?` |  | DJIT | unverified |
| `Get_Djit_Amin` | `DJITter:AMIN?` |  | DJIT | unverified |
| `Get_Djit_Bpfr` | `DJITter:BPFR?` |  | DJIT | unverified |
| `Get_Djit_Det` | `DJITter:DETector?` |  | DJIT | unverified |
| `Get_Djit_Ext` | `DJITter:EXTernal?` |  | DJIT | unverified |
| `Get_Djit_Filt` | `DJITter:FILTer?` |  | DJIT | unverified |
| `Get_Djit_Fmax` | `DJITter:FMAX?` |  | DJIT | unverified |
| `Get_Djit_Fmin` | `DJITter:FMIN?` |  | DJIT | unverified |
| `Get_Djit_Hpas` | `DJITter:HPASs?` |  | DJIT | unverified |
| `Get_Djit_Jdet` | `DJITter:JDETector?` |  | DJIT | unverified |
| `Get_Djit_Mmax` | `DJITter:MMAX?` |  | DJIT | unverified |
| `Get_Djit_Mmin` | `DJITter:MMIN?` |  | DJIT | unverified |
| `Get_Djit_Spe` | `DJITter:SPEed?` |  | DJIT | unverified |
| `Get_Djit_Step` | `DJITter:STEPs?` |  | DJIT | unverified |
| `Get_Djit_Swpt` | `DJITter:SWPType?` |  | DJIT | unverified |
| `Get_Djit_Unit` | `DJITter:UNIT?` |  | DJIT | unverified |
| `Get_Dlev_Amax` | `DLEVel:AMAX?` |  | DLEV | unverified |
| `Get_Dlev_Amin` | `DLEVel:AMIN?` |  | DLEV | unverified |
| `Get_Dlev_Ext` | `DLEVel:EXTernal?` |  | DLEV | unverified |
| `Get_Dlev_Fmax` | `DLEVel:FMAX?` |  | DLEV | unverified |
| `Get_Dlev_Fmin` | `DLEVel:FMIN?` |  | DLEV | unverified |
| `Get_Dlev_Lun` | `DLEVel:LUNit?` |  | DLEV | unverified |
| `Get_Dlev_Mmax` | `DLEVel:MMAX?` |  | DLEV | unverified |
| `Get_Dlev_Mmin` | `DLEVel:MMIN?` |  | DLEV | unverified |
| `Get_Dlev_Spe` | `DLEVel:SPEed?` |  | DLEV | unverified |
| `Get_Dlev_Step` | `DLEVel:STEPs?` |  | DLEV | unverified |
| `Get_Dlev_Swpt` | `DLEVel:SWPType?` |  | DLEV | unverified |
| `Get_Dlev_Unit` | `DLEVel:UNIT?` |  | DLEV | unverified |
| `Get_Dno_Amax` | `DNOise:AMAX?` |  | DNO | unverified |
| `Get_Dno_Amin` | `DNOise:AMIN?` |  | DNO | unverified |
| `Get_Dno_Bpfr` | `DNOise:BPFR?` |  | DNO | unverified |
| `Get_Dno_Ext` | `DNOise:EXTernal?` |  | DNO | unverified |
| `Get_Dno_Filt` | `DNOise:FILTer?` |  | DNO | unverified |
| `Get_Dno_Fmax` | `DNOise:FMAX?` |  | DNO | unverified |
| `Get_Dno_Fmin` | `DNOise:FMIN?` |  | DNO | unverified |
| `Get_Dno_Hpas` | `DNOise:HPASs?` |  | DNO | unverified |
| `Get_Dno_Lpas` | `DNOise:LPASs?` |  | DNO | unverified |
| `Get_Dno_Mmax` | `DNOise:MMAX?` |  | DNO | unverified |
| `Get_Dno_Mmin` | `DNOise:MMIN?` |  | DNO | unverified |
| `Get_Dno_Spe` | `DNOise:SPEed?` |  | DNO | unverified |
| `Get_Dno_Step` | `DNOise:STEPs?` |  | DNO | unverified |
| `Get_Dno_Swpt` | `DNOise:SWPType?` |  | DNO | unverified |
| `Get_Dno_Unit` | `DNOise:UNIT?` |  | DNO | unverified |
| `Get_Dno_Wtd` | `DNOise:WTD?` |  | DNO | unverified |
| `Get_Dost_Cons` | `:DOSTatus:CONS?` |  | DOST | unverified |
| `Get_Dost_Prof` | `:DOSTatus:PROF?` |  | DOST | unverified |
| `Get_Dost_Stdo` | `:DOSTatus:STDO?` |  | DOST | unverified |
| `Get_Dost_Val` | `DOSTatus:VALidity?` |  | DOST | unverified |
| `Get_Dph_Amax` | `DPHase:AMAX?` |  | DPH | unverified |
| `Get_Dph_Amin` | `DPHase:AMIN?` |  | DPH | unverified |
| `Get_Dph_Ext` | `DPHase:EXTernal?` |  | DPH | unverified |
| `Get_Dph_Fmax` | `DPHase:FMAX?` |  | DPH | unverified |
| `Get_Dph_Fmin` | `DPHase:FMIN?` |  | DPH | unverified |
| `Get_Dph_Lun` | `DPHase:LUNit?` |  | DPH | unverified |
| `Get_Dph_Mmax` | `DPHase:MMAX?` |  | DPH | unverified |
| `Get_Dph_Mmin` | `DPHase:MMIN?` |  | DPH | unverified |
| `Get_Dph_Rang` | `DPHase:RANGe?` |  | DPH | unverified |
| `Get_Dph_Spe` | `DPHase:SPEed?` |  | DPH | unverified |
| `Get_Dph_Step` | `DPHase:STEPs?` |  | DPH | unverified |
| `Get_Dph_Swpt` | `DPHase:SWPType?` |  | DPH | unverified |
| `Get_Dph_Unit` | `DPHase:UNIT?` |  | DPH | unverified |
| `Get_Drat_Amax` | `DRATio:AMAX?` |  | DRAT | unverified |
| `Get_Drat_Amin` | `DRATio:AMIN?` |  | DRAT | unverified |
| `Get_Drat_Ext` | `DRATio:EXTernal?` |  | DRAT | unverified |
| `Get_Drat_Fmax` | `DRATio:FMAX?` |  | DRAT | unverified |
| `Get_Drat_Fmin` | `DRATio:FMIN?` |  | DRAT | unverified |
| `Get_Drat_Lun` | `DRATio:LUNit?` |  | DRAT | unverified |
| `Get_Drat_Mmax` | `DRATio:MMAX?` |  | DRAT | unverified |
| `Get_Drat_Mmin` | `DRATio:MMIN?` |  | DRAT | unverified |
| `Get_Drat_Spe` | `DRATio:SPEed?` |  | DRAT | unverified |
| `Get_Drat_Step` | `DRATio:STEPs?` |  | DRAT | unverified |
| `Get_Drat_Swpt` | `DRATio:SWPType?` |  | DRAT | unverified |
| `Get_Drat_Unit` | `DRATio:UNIT?` |  | DRAT | unverified |
| `Get_Dthd_Amax` | `DTHD:AMAX?` |  | DTHD | unverified |
| `Get_Dthd_Amin` | `DTHD:AMIN?` |  | DTHD | unverified |
| `Get_Dthd_Ext` | `DTHD:EXTernal?` |  | DTHD | unverified |
| `Get_Dthd_Filt` | `DTHD:FILTer?` |  | DTHD | unverified |
| `Get_Dthd_Fmax` | `DTHD:FMAX?` |  | DTHD | unverified |
| `Get_Dthd_Fmin` | `DTHD:FMIN?` |  | DTHD | unverified |
| `Get_Dthd_Hpas` | `DTHD:HPASs?` |  | DTHD | unverified |
| `Get_Dthd_Lpas` | `DTHD:LPASs?` |  | DTHD | unverified |
| `Get_Dthd_Lun` | `DTHD:LUNit?` |  | DTHD | unverified |
| `Get_Dthd_Mmax` | `DTHD:MMAX?` |  | DTHD | unverified |
| `Get_Dthd_Mmin` | `DTHD:MMIN?` |  | DTHD | unverified |
| `Get_Dthd_Notc` | `DTHD:NOTChfreq?` |  | DTHD | unverified |
| `Get_Dthd_Spe` | `DTHD:SPEed?` |  | DTHD | unverified |
| `Get_Dthd_Step` | `DTHD:STEP?` |  | DTHD | unverified |
| `Get_Dthd_Swpt` | `DTHD:SWPType?` |  | DTHD | unverified |
| `Get_Dthd_Tun` | `DTHD:TUNe?` |  | DTHD | unverified |
| `Get_Dthd_Unit` | `DTHD:UNIT?` |  | DTHD | unverified |
| `Get_Dthd_Wtd` | `DTHD:WTD?` |  | DTHD | unverified |
| `Get_Dxt_Amax` | `DXTalk:AMAX?` |  | DXT | unverified |
| `Get_Dxt_Amin` | `DXTalk:AMIN?` |  | DXT | unverified |
| `Get_Dxt_Ext` | `DXTalk:EXTernal?` |  | DXT | unverified |
| `Get_Dxt_Fmax` | `DXTalk:FMAX?` |  | DXT | unverified |
| `Get_Dxt_Fmin` | `DXTalk:FMIN?` |  | DXT | unverified |
| `Get_Dxt_Lun` | `DXTalk:LUNit?` |  | DXT | unverified |
| `Get_Dxt_Mmax` | `DXTalk:MMAX?` |  | DXT | unverified |
| `Get_Dxt_Mmin` | `DXTalk:MMIN?` |  | DXT | unverified |
| `Get_Dxt_Spe` | `DXTalk:SPEed?` |  | DXT | unverified |
| `Get_Dxt_Step` | `DXTalk:STEPs?` |  | DXT | unverified |
| `Get_Dxt_Swpt` | `DXTalk:SWPType?` |  | DXT | unverified |
| `Get_Dxt_Unit` | `DXTalk:UNIT?` |  | DXT | unverified |
| `Get_Genl_Fmax` | `GENLoad:FMAX?` |  | GENL | unverified |
| `Get_Genl_Fmin` | `GENLoad:FMIN?` |  | GENL | unverified |
| `Get_Genl_Mmax` | `GENLoad:MMAX?` |  | GENL | unverified |
| `Get_Genl_Mmin` | `GENLoad:MMIN?` |  | GENL | unverified |
| `Get_Genl_Spe` | `GENLoad:SPEed?` |  | GENL | unverified |
| `Get_Genl_Step` | `GENLoad:STEPs?` |  | GENL | unverified |
| `Get_Genl_Unit` | `GENLoad:UNIT?` |  | GENL | unverified |
| `Get_Imd_Amax` | `IMD:AMAX?` |  | IMD | unverified |
| `Get_Imd_Amin` | `IMD:AMIN?` |  | IMD | unverified |
| `Get_Imd_Lun` | `IMD:LUNit?` |  | IMD | unverified |
| `Get_Imd_Mmax` | `IMD:MMAX?` |  | IMD | unverified |
| `Get_Imd_Mmin` | `IMD:MMIN?` |  | IMD | unverified |
| `Get_Imd_Spe` | `IMD:SPEed?` |  | IMD | unverified |
| `Get_Imd_Steps` | `IMD:STEPS?` |  | IMD | unverified |
| `Get_Imd_Unit` | `IMD:UNIT?` |  | IMD | unverified |
| `Get_Lev_Amax` | `LEVel:AMAX?` |  | LEV | unverified |
| `Get_Lev_Amin` | `LEVel:AMIN?` |  | LEV | unverified |
| `Get_Lev_Ext` | `LEVel:EXTernal?` |  | LEV | unverified |
| `Get_Lev_Fmax` | `LEVel:FMAX?` |  | LEV | unverified |
| `Get_Lev_Fmin` | `LEVel:FMIN?` |  | LEV | unverified |
| `Get_Lev_Lun` | `LEVel:LUNit?` |  | LEV | unverified |
| `Get_Lev_Mmax` | `LEVel:MMAX?` |  | LEV | unverified |
| `Get_Lev_Mmin` | `LEVel:MMIN?` |  | LEV | unverified |
| `Get_Lev_Spe` | `LEVel:SPEed?` |  | LEV | unverified |
| `Get_Lev_Step` | `LEVel:STEPs?` |  | LEV | unverified |
| `Get_Lev_Swpt` | `LEVel:SWPType?` |  | LEV | unverified |
| `Get_Lev_Unit` | `LEVel:UNIT?` |  | LEV | unverified |
| `Read_Ch_A_Only` | `M1?` |  | Read Commands |  |
| `Read_Ch_B_Only` | `M2?` |  | Read Commands |  |
| `Get_Nois_Amax` | `NOISe:AMAX?` |  | NOIS | unverified |
| `Get_Nois_Amin` | `NOISe:AMIN?` |  | NOIS | unverified |
| `Get_Nois_Bpfr` | `NOISe:BPFR?` |  | NOIS | unverified |
| `Get_Nois_Ext` | `NOISe:EXTernal?` |  | NOIS | unverified |
| `Get_Nois_Filt` | `NOISe:FILTer?` |  | NOIS | unverified |
| `Get_Nois_Fmax` | `NOISe:FMAX?` |  | NOIS | unverified |
| `Get_Nois_Fmin` | `NOISe:FMIN?` |  | NOIS | unverified |
| `Get_Nois_Hpas` | `NOISe:HPASs?` |  | NOIS | unverified |
| `Get_Nois_Lpas` | `NOISe:LPASs?` |  | NOIS | unverified |
| `Get_Nois_Mmax` | `NOISe:MMAX?` |  | NOIS | unverified |
| `Get_Nois_Mmin` | `NOISe:MMIN?` |  | NOIS | unverified |
| `Get_Nois_Spe` | `NOISe:SPEed?` |  | NOIS | unverified |
| `Get_Nois_Step` | `NOISe:STEPs?` |  | NOIS | unverified |
| `Get_Nois_Swpt` | `NOISe:SWPType?` |  | NOIS | unverified |
| `Get_Nois_Unit` | `NOISe:UNIT?` |  | NOIS | unverified |
| `Get_Nois_Wtd` | `NOISe:WTD?` |  | NOIS | unverified |
| `Get_Phas_Amax` | `PHASe:AMAX?` |  | PHAS | unverified |
| `Get_Phas_Amin` | `PHASe:AMIN?` |  | PHAS | unverified |
| `Get_Phas_Ave` | `PHASe:AVErage?` |  | PHAS | unverified |
| `Get_Phas_Ext` | `PHASe:EXTernal?` |  | PHAS | unverified |
| `Get_Phas_Fmax` | `PHASe:FMAX?` |  | PHAS | unverified |
| `Get_Phas_Fmin` | `PHASe:FMIN?` |  | PHAS | unverified |
| `Get_Phas_Lun` | `PHASe:LUNit?` |  | PHAS | unverified |
| `Get_Phas_Mmax` | `PHASe:MMAX?` |  | PHAS | unverified |
| `Get_Phas_Mmin` | `PHASe:MMIN?` |  | PHAS | unverified |
| `Get_Phas_Rang` | `PHASe:RANGe?` |  | PHAS | unverified |
| `Get_Phas_Spe` | `PHASe:SPEed?` |  | PHAS | unverified |
| `Get_Phas_Step` | `PHASe:STEPs?` |  | PHAS | unverified |
| `Get_Phas_Swpt` | `PHASe:SWPType?` |  | PHAS | unverified |
| `Get_Phas_Unit` | `PHASe:UNIT?` |  | PHAS | unverified |
| `Get_Rat_Amax` | `RATio:AMAX?` |  | RAT | unverified |
| `Get_Rat_Amin` | `RATio:AMIN?` |  | RAT | unverified |
| `Get_Rat_Ext` | `RATio:EXTernal?` |  | RAT | unverified |
| `Get_Rat_Fmax` | `RATio:FMAX?` |  | RAT | unverified |
| `Get_Rat_Fmin` | `RATio:FMIN?` |  | RAT | unverified |
| `Get_Rat_Lun` | `RATio:LUNit?` |  | RAT | unverified |
| `Get_Rat_Mmax` | `RATio:MMAX?` |  | RAT | unverified |
| `Get_Rat_Mmin` | `RATio:MMIN?` |  | RAT | unverified |
| `Get_Rat_Mode` | `RATio:MODE?` |  | RAT | unverified |
| `Get_Rat_Spe` | `RATio:SPEed?` |  | RAT | unverified |
| `Get_Rat_Step` | `RATio:STEPs?` |  | RAT | unverified |
| `Get_Rat_Swpt` | `RATio:SWPType?` |  | RAT | unverified |
| `Get_Rat_Unit` | `RATio:UNIT?` |  | RAT | unverified |
| `Get_Sin_Hpas` | `SINad:HPASs?` |  | SIN | unverified |
| `Get_Sin_Lpas` | `SINad:LPASs?` |  | SIN | unverified |
| `Get_Sin_Lun` | `SINad:LUNit?` |  | SIN | unverified |
| `Get_Sin_Mmax` | `SINad:MMAX?` |  | SIN | unverified |
| `Get_Sin_Mmin` | `SINad:MMIN?` |  | SIN | unverified |
| `Get_Sin_Notc` | `SINad:NOTChfreq?` |  | SIN | unverified |
| `Get_Sin_Pres` | `SINad:PRESet?` |  | SIN | unverified |
| `Get_Sin_Tun` | `SINad:TUNe?` |  | SIN | unverified |
| `Get_Sin_Unit` | `SINad:UNIT?` |  | SIN | unverified |
| `Get_Thd_Amax` | `THD:AMAX?` |  | THD | unverified |
| `Get_Thd_Amin` | `THD:AMIN?` |  | THD | unverified |
| `Get_Thd_Ext` | `THD:EXTernal?` |  | THD | unverified |
| `Get_Thd_Filt` | `THD:FILTer?` |  | THD | unverified |
| `Get_Thd_Fmax` | `THD:FMAX?` |  | THD | unverified |
| `Get_Thd_Fmin` | `THD:FMIN?` |  | THD | unverified |
| `Get_Thd_Hpas` | `THD:HPASs?` |  | THD | unverified |
| `Get_Thd_Lpas` | `THD:LPASs?` |  | THD | unverified |
| `Get_Thd_Lun` | `THD:LUNit?` |  | THD | unverified |
| `Get_Thd_Mmax` | `THD:MMAX?` |  | THD | unverified |
| `Get_Thd_Mmin` | `THD:MMIN?` |  | THD | unverified |
| `Get_Thd_Notc` | `THD:NOTChfreq?` |  | THD | unverified |
| `Get_Thd_Spe` | `THD:SPEed?` |  | THD | unverified |
| `Get_Thd_Step` | `THD:STEPs?` |  | THD | unverified |
| `Get_Thd_Swpt` | `THD:SWPType?` |  | THD | unverified |
| `Get_Thd_Tun` | `THD:TUNe?` |  | THD | unverified |
| `Get_Thd_Unit` | `THD:UNIT?` |  | THD | unverified |
| `Get_Thd_Wtd` | `THD:WTD?` |  | THD | unverified |
| `Get_Wf_Det` | `WF:DETector?` |  | WF | unverified |
| `Get_Wf_Filt` | `WF:FILTer?` |  | WF | unverified |
| `Get_Wf_Lun` | `WF:LUNit?` |  | WF | unverified |
| `Get_Wf_Mmax` | `WF:MMAX?` |  | WF | unverified |
| `Get_Wf_Mmin` | `WF:MMIN?` |  | WF | unverified |
| `Get_Wf_Resp` | `WF:RESPonse?` |  | WF | unverified |
| `Get_Wf_Unit` | `WF:UNIT?` |  | WF | unverified |
| `Get_Wf_Wfun` | `WF:WFUNit?` |  | WF | unverified |
| `Get_Xtal_Amax` | `XTALk:AMAX?` |  | XTAL | unverified |
| `Get_Xtal_Amin` | `XTALk:AMIN?` |  | XTAL | unverified |
| `Get_Xtal_Ext` | `XTALk:EXTernal?` |  | XTAL | unverified |
| `Get_Xtal_Fmax` | `XTALk:FMAX?` |  | XTAL | unverified |
| `Get_Xtal_Fmin` | `XTALk:FMIN?` |  | XTAL | unverified |
| `Get_Xtal_Lun` | `XTALk:LUNit?` |  | XTAL | unverified |
| `Get_Xtal_Mmax` | `XTALk:MMAX?` |  | XTAL | unverified |
| `Get_Xtal_Mmin` | `XTALk:MMIN?` |  | XTAL | unverified |
| `Get_Xtal_Spe` | `XTALk:SPEed?` |  | XTAL | unverified |
| `Get_Xtal_Step` | `XTALk:STEPs?` |  | XTAL | unverified |
| `Get_Xtal_Swpt` | `XTALk:SWPType?` |  | XTAL | unverified |
| `Get_Xtal_Unit` | `XTALk:UNIT?` |  | XTAL | unverified |

## `set` — writes one value (276)

| Command | SCPI | Argument | Group | |
|---|---|---|---|---|
| `Set_Acm_Lun` | `:ACM:LUN <value>` | PCT · OFF | ACM | unverified |
| `Set_Acm_Mmax` | `ACMains:MMAX <value>` | numeric | ACM | unverified |
| `Set_Acm_Mmin` | `ACMains:MMIN <value>` | numeric | ACM | unverified |
| `Set_Acm_Unit` | `ACMains:UNIT <value>` | V | ACM | unverified |
| `Set_Ampl_Amax` | `:AMPL:AMAX <value>` | numeric | AMPL | unverified |
| `Set_Ampl_Amin` | `:AMPL:AMIN <value>` | numeric | AMPL | unverified |
| `Set_Ampl_Bpfr` | `AMPLitude:BPFR <value>` | unknown | AMPL | unverified |
| `Set_Ampl_Ext` | `AMPLitude:EXTernal <value>` | OFF · ON | AMPL | unverified |
| `Set_Ampl_Filt` | `AMPLitude:FILTer <value>` | SEL · WTD · UNWT | AMPL | unverified |
| `Set_Ampl_Fmax` | `AMPLitude:FMAX <value>` | numeric | AMPL | unverified |
| `Set_Ampl_Fmin` | `AMPLitude:FMIN <value>` | numeric | AMPL | unverified |
| `Set_Ampl_Hpas` | `AMPLitude:HPASs <value>` | ON · OFF | AMPL | unverified |
| `Set_Ampl_Lpas` | `AMPLitude:LPASs <value>` | R22 · Q22 · R30 · R80 · R300 | AMPL | unverified |
| `Set_Ampl_Mmax` | `AMPLitude:MMAX <value>` | numeric | AMPL | unverified |
| `Set_Ampl_Mmin` | `AMPLitude:MMIN <value>` | numeric | AMPL | unverified |
| `Set_Ampl_Spe` | `AMPLitude:SPEed <value>` | FAST · MED · SLOW | AMPL | unverified |
| `Set_Ampl_Swpt` | `AMPLitude:SWPType <value>` | FREQ · AMPL | AMPL | unverified |
| `Set_Ampl_Unit` | `AMPLitude:UNIT <value>` | V · DBV · DBU · DBM · DBR · DBG · W | AMPL | unverified |
| `Set_Ampl_Wtd` | `AMPLitude:WTD <value>` | AUX1 · AUX2 · IEC · RMSC · CCIR2K · QPKC · ARMC | AMPL | unverified |
| `Set_Damp_Amax` | `:DAMP:AMAX <value>` | numeric | DAMP | unverified |
| `Set_Damp_Amin` | `DAMPlitude:AMIN <value>` | numeric | DAMP | unverified |
| `Set_Damp_Bpfr` | `DAMPlitude:BPFR <value>` | unknown | DAMP | unverified |
| `Set_Damp_Ext` | `DAMPlitude:EXTernal <value>` | OFF · ON | DAMP | unverified |
| `Set_Damp_Filt` | `DAMPlitude:FILTer <value>` | SEL · WTD · UNWT | DAMP | unverified |
| `Set_Damp_Fmax` | `DAMPlitude:FMAX <value>` | numeric | DAMP | unverified |
| `Set_Damp_Fmin` | `DAMPlitude:FMIN <value>` | numeric | DAMP | unverified |
| `Set_Damp_Hpas` | `DAMPlitude:HPASs <value>` | enum | DAMP | unverified |
| `Set_Damp_Lpas` | `DAMPlitude:LPASs <value>` | R15 · R20 · HALF · R22 · Q22 | DAMP | unverified |
| `Set_Damp_Mmax` | `DAMPlitude:MMAX <value>` | numeric | DAMP | unverified |
| `Set_Damp_Mmin` | `DAMPlitude:MMIN <value>` | numeric | DAMP | unverified |
| `Set_Damp_Spe` | `DAMPlitude:SPEed <value>` | FAST · MED · SLOW | DAMP | unverified |
| `Set_Damp_Step` | `DAMPlitude:STEP <value>` | integer | DAMP | unverified |
| `Set_Damp_Swpt` | `DAMPlitude:SWPType <value>` | FREQ · AMPL | DAMP | unverified |
| `Set_Damp_Unit` | `DAMPlitude:UNIT <value>` | FFS · DBFS · DBR | DAMP | unverified |
| `Set_Damp_Wtd` | `DAMPlitude:WTD <value>` | IEC · RMSC · CCIR2K · QPKC | DAMP | unverified |
| `Set_Dchk_Bits` | `:DCHK:BITS <value>` | unknown | DCHK | unverified |
| `Set_Dchk_Dbit` | `DCHK:DBITs <value>` | ACTV · ACTL | DCHK | unverified |
| `Set_Dchk_Dun` | `DCHK:DUNit <value>` | DEC · HEX | DCHK | unverified |
| `Set_Dchk_Mmax` | `DCHK:MMAX <value>` | numeric | DCHK | unverified |
| `Set_Dchk_Mmin` | `DCHK:MMIN <value>` | numeric | DCHK | unverified |
| `Set_Dchk_Unit` | `DCHK:UNIT <value>` | enum | DCHK | unverified |
| `Set_Dimd_Amax` | `:DIMD:AMAX <value>` | numeric | DIMD | unverified |
| `Set_Dimd_Amin` | `DIMD:AMIN <value>` | numeric | DIMD | unverified |
| `Set_Dimd_Lun` | `DIMD:LUNit <value>` | FFS · DBFS · DBR | DIMD | unverified |
| `Set_Dimd_Mmax` | `DIMD:MMAX <value>` | numeric | DIMD | unverified |
| `Set_Dimd_Mmin` | `DIMD:MMIN <value>` | numeric | DIMD | unverified |
| `Set_Dimd_Spe` | `DIMD:SPEed <value>` | FAST · MED · SLOW | DIMD | unverified |
| `Set_Dimd_Step` | `DIMD:STEPs <value>` | integer | DIMD | unverified |
| `Set_Dimd_Unit` | `DIMD:UNIT <value>` | PCT · DB | DIMD | unverified |
| `Set_Dio_Ddref` | `:DIO:DDREF <value>` | OUTB · OUTF · REFB · REFF | DIO | unverified |
| `Set_Dio_Dir` | `DIO:DIResolution <value>` | numeric | DIO | unverified |
| `Set_Dio_Dref` | `DIO:DREF <value>` | unknown | DIO | unverified |
| `Set_Dio_Dun` | `DIO:DUNit <value>` | UI · SMP · SEC | DIO | unverified |
| `Set_Dio_Frqr` | `DIO:FRQRef <value>` | MEAS · OUTP · STAT | DIO | unverified |
| `Set_Dio_Mmax` | `DIO:MMAX <value>` | numeric | DIO | unverified |
| `Set_Dio_Mmin` | `DIO:MMIN <value>` | numeric | DIO | unverified |
| `Set_Dio_Unit` | `DIO:UNIT <value>` | HZ · PPM | DIO | unverified |
| `Set_Dist_Cod` | `:DIST:COD <value>` | unknown | DIST | unverified |
| `Set_Djit_Amax` | `:DJIT:AMAX <value>` | numeric | DJIT | unverified |
| `Set_Djit_Amin` | `DJITter:AMIN <value>` | numeric | DJIT | unverified |
| `Set_Djit_Bpfr` | `DJITter:BPFR <value>` | unknown | DJIT | unverified |
| `Set_Djit_Det` | `DJITter:DETector <value>` | enum | DJIT | unverified |
| `Set_Djit_Ext` | `DJITter:EXTernal <value>` | OFF · ON | DJIT | unverified |
| `Set_Djit_Filt` | `DJITter:FILTer <value>` | SEL · UNWT | DJIT | unverified |
| `Set_Djit_Fmax` | `DJITter:FMAX <value>` | numeric | DJIT | unverified |
| `Set_Djit_Fmin` | `DJITter:FMIN <value>` | numeric | DJIT | unverified |
| `Set_Djit_Hpas` | `DJITter:HPASs <value>` | enum | DJIT | unverified |
| `Set_Djit_Jdet` | `DJITter:JDETector <value>` | PEAK · RMS | DJIT | unverified |
| `Set_Djit_Mmax` | `DJITter:MMAX <value>` | numeric | DJIT | unverified |
| `Set_Djit_Mmin` | `DJITter:MMIN <value>` | numeric | DJIT | unverified |
| `Set_Djit_Spe` | `DJITter:SPEed <value>` | FAST · MED · SLOW | DJIT | unverified |
| `Set_Djit_Step` | `DJITter:STEP <value>` | integer | DJIT | unverified |
| `Set_Djit_Swpt` | `DJITter:SWPType <value>` | FREQ · AMPL | DJIT | unverified |
| `Set_Djit_Unit` | `DJITter:UNIT <value>` | UI · SEC | DJIT | unverified |
| `Set_Dlev_Amax` | `:DLEV:AMAX <value>` | numeric | DLEV | unverified |
| `Set_Dlev_Amin` | `DLEVel:AMIN <value>` | numeric | DLEV | unverified |
| `Set_Dlev_Ext` | `DLEVel:EXTernal <value>` | OFF · ON | DLEV | unverified |
| `Set_Dlev_Lun` | `DLEVel:LUNit <value>` | FFS · DBFS · DBR | DLEV | unverified |
| `Set_Dlev_Mmax` | `DLEVel:MMAX <value>` | numeric | DLEV | unverified |
| `Set_Dlev_Mmin` | `DLEVel:MMIN <value>` | numeric | DLEV | unverified |
| `Set_Dlev_Spe` | `DLEVel:SPEed <value>` | FAST · MED · SLOW | DLEV | unverified |
| `Set_Dlev_Step` | `DLEVel:STEP <value>` | integer | DLEV | unverified |
| `Set_Dlev_Swpt` | `DLEVel:SWPType <value>` | FREQ · AMPL | DLEV | unverified |
| `Set_Dlev_Unit` | `DLEVel:UNIT <value>` | FFS · DBFS · DBR | DLEV | unverified |
| `Set_Dno_Amax` | `DNOise:AMAX <value>` | numeric | DNO | unverified |
| `Set_Dno_Amin` | `DNOise:AMIN <value>` | numeric | DNO | unverified |
| `Set_Dno_Bpfr` | `DNOise:BPFR <value>` | unknown | DNO | unverified |
| `Set_Dno_Ext` | `DNOise:EXTernal <value>` | OFF · ON | DNO | unverified |
| `Set_Dno_Filt` | `DNOise:FILTer <value>` | SEL · WTD · UNWTD | DNO | unverified |
| `Set_Dno_Fmax` | `DNOise:FMAX <value>` | numeric | DNO | unverified |
| `Set_Dno_Fmin` | `DNOise:FMIN <value>` | numeric | DNO | unverified |
| `Set_Dno_Hpas` | `DNOise:HPASs <value>` | enum | DNO | unverified |
| `Set_Dno_Lpas` | `DNOise:LPASs <value>` | R15 · R20 · HALF · R22 · Q22 | DNO | unverified |
| `Set_Dno_Mmax` | `DNOise:MMAX <value>` | numeric | DNO | unverified |
| `Set_Dno_Mmin` | `DNOise:MMIN <value>` | numeric | DNO | unverified |
| `Set_Dno_Spe` | `DNOise:SPEed <value>` | FAST · MED · SLOW | DNO | unverified |
| `Set_Dno_Step` | `DNOise:STEP <value>` | integer | DNO | unverified |
| `Set_Dno_Swpt` | `DNOise:SWPType <value>` | FREQ · AMPL | DNO | unverified |
| `Set_Dno_Unit` | `DNOise:UNIT <value>` | FFS · DBFS · DBR | DNO | unverified |
| `Set_Dno_Wtd` | `DNOise:WTD <value>` | IEC · RMSC · CCIR2K · QPKC | DNO | unverified |
| `Set_Dost_Cons` | `DOSTatus:CONS <value>` | unknown | DOST | unverified |
| `Set_Dost_Prof` | `DOSTatus:PROF <value>` | unknown | DOST | unverified |
| `Set_Dost_Stdo` | `DOSTatus:STDO <value>` | enum | DOST | unverified |
| `Set_Dost_Val` | `DOSTatus:VALidity <value>` | numeric | DOST | unverified |
| `Set_Dph_Amax` | `DPHase:AMAX <value>` | numeric | DPH | unverified |
| `Set_Dph_Amin` | `DPHase:AMIN <value>` | numeric | DPH | unverified |
| `Set_Dph_Ext` | `DPHase:EXTernal <value>` | OFF · ON | DPH | unverified |
| `Set_Dph_Fmax` | `DPHase:FMAX <value>` | numeric | DPH | unverified |
| `Set_Dph_Fmin` | `DPHase:FMIN <value>` | numeric | DPH | unverified |
| `Set_Dph_Lun` | `DPHase:LUNit <value>` | FFS · DBFS · DBR | DPH | unverified |
| `Set_Dph_Mmax` | `DPHase:MMAX <value>` | numeric | DPH | unverified |
| `Set_Dph_Mmin` | `DPHase:MMIN <value>` | numeric | DPH | unverified |
| `Set_Dph_Rang` | `DPHase:RANGe <value>` | DEG90 · DEG180 · DEG270 | DPH | unverified |
| `Set_Dph_Spe` | `DPHase:SPEed <value>` | FAST · MED · SLOW | DPH | unverified |
| `Set_Dph_Step` | `DPHase:STEP <value>` | integer | DPH | unverified |
| `Set_Dph_Swpt` | `DPHase:SWPType <value>` | FREQ · AMPL | DPH | unverified |
| `Set_Dph_Unit` | `DPHase:UNIT <value>` | DEG | DPH | unverified |
| `Set_Drat_Amax` | `:DRAT:AMAX <value>` | numeric | DRAT | unverified |
| `Set_Drat_Amin` | `DRATio:AMIN <value>` | numeric | DRAT | unverified |
| `Set_Drat_Ext` | `DRATio:EXTernal <value>` | OFF · ON | DRAT | unverified |
| `Set_Drat_Fmax` | `DRATio:FMAX <value>` | numeric | DRAT | unverified |
| `Set_Drat_Fmin` | `DRATio:FMIN <value>` | numeric | DRAT | unverified |
| `Set_Drat_Lun` | `DRATio:LUNit <value>` | FFS · DBFS · DBR | DRAT | unverified |
| `Set_Drat_Mmax` | `DRATio:MMAX <value>` | numeric | DRAT | unverified |
| `Set_Drat_Mmin` | `DRATio:MMIN <value>` | numeric | DRAT | unverified |
| `Set_Drat_Spe` | `DRATio:SPEed <value>` | FAST · MED · SLOW | DRAT | unverified |
| `Set_Drat_Step` | `DRATio:STEP <value>` | integer | DRAT | unverified |
| `Set_Drat_Swpt` | `DRATio:SWPType <value>` | FREQ · AMPL | DRAT | unverified |
| `Set_Drat_Unit` | `DRATio:UNIT <value>` | DB | DRAT | unverified |
| `Set_Dthd_Amax` | `:DTHD:AMAX <value>` | numeric | DTHD | unverified |
| `Set_Dthd_Amin` | `DTHD:AMIN <value>` | numeric | DTHD | unverified |
| `Set_Dthd_Ext` | `DTHD:EXTernal <value>` | OFF · ON | DTHD | unverified |
| `Set_Dthd_Filt` | `DTHD:FILTer <value>` | WTD · UNWT · AVER | DTHD | unverified |
| `Set_Dthd_Fmax` | `DTHD:FMAX <value>` | numeric | DTHD | unverified |
| `Set_Dthd_Fmin` | `DTHD:FMIN <value>` | numeric | DTHD | unverified |
| `Set_Dthd_Hpas` | `DTHD:HPASs <value>` | enum | DTHD | unverified |
| `Set_Dthd_Lpas` | `DTHD:LPASs <value>` | R15 · R20 · HALF · R22 · Q22 | DTHD | unverified |
| `Set_Dthd_Lun` | `DTHD:LUNit <value>` | FFS · DBFS · DBR | DTHD | unverified |
| `Set_Dthd_Mmax` | `DTHD:MMAX <value>` | numeric | DTHD | unverified |
| `Set_Dthd_Mmin` | `DTHD:MMIN <value>` | numeric | DTHD | unverified |
| `Set_Dthd_Notc` | `DTHD:NOTChfreq <value>` | unknown | DTHD | unverified |
| `Set_Dthd_Spe` | `DTHD:SPEed <value>` | FAST · MED · SLOW | DTHD | unverified |
| `Set_Dthd_Step` | `DTHD:STEP <value>` | integer | DTHD | unverified |
| `Set_Dthd_Swpt` | `DTHD:SWPType <value>` | FREQ · AMPL | DTHD | unverified |
| `Set_Dthd_Tun` | `DTHD:TUNe <value>` | AUT · GENT · FIXT | DTHD | unverified |
| `Set_Dthd_Unit` | `DTHD:UNIT <value>` | PCT · DB · FFS · DBFS · DBR | DTHD | unverified |
| `Set_Dthd_Wtd` | `DTHD:WTD <value>` | unknown | DTHD | unverified |
| `Set_Dxt_Amax` | `DXTalk:AMAX <value>` | numeric | DXT | unverified |
| `Set_Dxt_Amin` | `DXTalk:AMIN <value>` | numeric | DXT | unverified |
| `Set_Dxt_Ext` | `DXTalk:EXTernal <value>` | OFF · ON | DXT | unverified |
| `Set_Dxt_Fmax` | `DXTalk:FMAX <value>` | numeric | DXT | unverified |
| `Set_Dxt_Fmin` | `DXTalk:FMIN <value>` | numeric | DXT | unverified |
| `Set_Dxt_Lun` | `DXTalk:LUNit <value>` | FFS · DBFS · DBR | DXT | unverified |
| `Set_Dxt_Mmax` | `DXTalk:MMAX <value>` | numeric | DXT | unverified |
| `Set_Dxt_Mmin` | `DXTalk:MMIN <value>` | numeric | DXT | unverified |
| `Set_Dxt_Spe` | `DXTalk:SPEed <value>` | FAST · MED · SLOW | DXT | unverified |
| `Set_Dxt_Step` | `DXTalk:STEP <value>` | integer | DXT | unverified |
| `Set_Dxt_Swpt` | `DXTalk:SWPType <value>` | FREQ · AMPL | DXT | unverified |
| `Set_Dxt_Unit` | `DXTalk:UNIT <value>` | enum | DXT | unverified |
| `Set_Amplitude` | `:GAMPlitude <amp>` | numeric | Set Signal Parameters |  |
| `Set_Genl_Fmax` | `:GENL:FMAX <value>` | numeric | GENL | unverified |
| `Set_Genl_Fmin` | `GENLoad:FMIN <value>` | numeric | GENL | unverified |
| `Set_Genl_Mmax` | `GENLoad:MMAX <value>` | numeric | GENL | unverified |
| `Set_Genl_Mmin` | `GENLoad:MMIN <value>` | numeric | GENL | unverified |
| `Set_Genl_Spe` | `GENLoad:SPEed <value>` | FAST · MED · SLOW | GENL | unverified |
| `Set_Genl_Step` | `GENLoad:STEPs <value>` | integer | GENL | unverified |
| `Set_Genl_Unit` | `GENLoad:UNIT <value>` | OHM | GENL | unverified |
| `Set_Frequency` | `:GFREquency <freq>` | numeric | Set Signal Parameters |  |
| `Set_Imd_Amax` | `:IMD:AMAX <value>` | numeric | IMD | unverified |
| `Set_Imd_Amin` | `IMD:AMIN <value>` | numeric | IMD | unverified |
| `Set_Imd_Lun` | `IMD:LUNit <value>` | V · DBV · DBU · DBM · DBR · DBG · W · OFF | IMD | unverified |
| `Set_Imd_Mmax` | `IMD:MMAX <value>` | numeric | IMD | unverified |
| `Set_Imd_Mmin` | `IMD:MMIN <value>` | numeric | IMD | unverified |
| `Set_Imd_Spe` | `IMD:SPEed <value>` | FAST · MED · SLOW | IMD | unverified |
| `Set_Imd_Unit` | `IMD:UNIT <value>` | PCT · DB | IMD | unverified |
| `Set_Input` | `INPUT <state>` | OFF · ON | General | unverified |
| `Set_Lev_Amax` | `:LEV:AMAX <value>` | numeric | LEV | unverified |
| `Set_Lev_Amin` | `LEVel:AMIN <value>` | numeric | LEV | unverified |
| `Set_Lev_Ext` | `LEVel:EXTernal <value>` | OFF · ON | LEV | unverified |
| `Set_Lev_Lun` | `LEVel:LUNit <value>` | V · DBV · DBU · DBM · DBR · DBG · W | LEV | unverified |
| `Set_Lev_Mmax` | `LEVel:MMAX <value>` | numeric | LEV | unverified |
| `Set_Lev_Mmin` | `LEVel:MMIN <value>` | numeric | LEV | unverified |
| `Set_Lev_Spe` | `LEVel:SPEed <value>` | FAST · MED · SLOW | LEV | unverified |
| `Set_Lev_Step` | `LEVel:STEPs <value>` | integer | LEV | unverified |
| `Set_Lev_Swpt` | `LEVel:SWPType <value>` | FREQ · AMPL | LEV | unverified |
| `Set_Lev_Unit` | `LEVel:UNIT <value>` | V · DBV · DBU · DBM · DBR · DBG · W | LEV | unverified |
| `Set_Mode` | `MODE <value>` |  | General | unverified |
| `Set_Nois_Amax` | `:NOIS:AMAX <value>` | numeric | NOIS | unverified |
| `Set_Nois_Amin` | `NOISe:AMIN <value>` | numeric | NOIS | unverified |
| `Set_Nois_Bpfr` | `NOISe:BPFR <value>` | unknown | NOIS | unverified |
| `Set_Nois_Ext` | `NOISe:EXTernal <value>` | OFF · ON | NOIS | unverified |
| `Set_Nois_Filt` | `NOISe:FILTer <value>` | SEL · WTD · UNWTD | NOIS | unverified |
| `Set_Nois_Fmax` | `NOISe:FMAX <value>` | numeric | NOIS | unverified |
| `Set_Nois_Fmin` | `NOISe:FMIN <value>` | numeric | NOIS | unverified |
| `Set_Nois_Hpas` | `NOISe:HPASs <value>` | ON · OFF | NOIS | unverified |
| `Set_Nois_Lpas` | `NOISe:LPASs <value>` | R22 · Q22 · R30 · R80 · R300 | NOIS | unverified |
| `Set_Nois_Mmax` | `NOISe:MMAX <value>` | numeric | NOIS | unverified |
| `Set_Nois_Mmin` | `NOISe:MMIN <value>` | numeric | NOIS | unverified |
| `Set_Nois_Spe` | `NOISe:SPEed <value>` | FAST · MED · SLOW | NOIS | unverified |
| `Set_Nois_Step` | `NOISe:STEPs <value>` | integer | NOIS | unverified |
| `Set_Nois_Swpt` | `NOISe:SWPType <value>` | FREQ · AMPL | NOIS | unverified |
| `Set_Nois_Unit` | `NOISe:UNIT <value>` | V · DBV · DBU · DBM · DBG · W · DB | NOIS | unverified |
| `Set_Nois_Wtd` | `NOISe:WTD <value>` | AUX1 · AUX2 · IEC · RMSC · CCIR2K · QPKC · ARMC | NOIS | unverified |
| `Set_Phas_Amax` | `:PHAS:AMAX <value>` | numeric | PHAS | unverified |
| `Set_Phas_Amin` | `PHASe:AMIN <value>` | numeric | PHAS | unverified |
| `Set_Phas_Ext` | `PHASe:EXTernal <value>` | OFF · ON | PHAS | unverified |
| `Set_Phas_Fmax` | `PHASe:FMAX <value>` | numeric | PHAS | unverified |
| `Set_Phas_Fmin` | `PHASe:FMIN <value>` | numeric | PHAS | unverified |
| `Set_Phas_Lun` | `PHASe:LUNit <value>` | V · DBV · DBU · DBM · DBR · DBG · W · OFF | PHAS | unverified |
| `Set_Phas_Mmax` | `PHASe:MMAX <value>` | numeric | PHAS | unverified |
| `Set_Phas_Mmin` | `PHASe:MMIN <value>` | numeric | PHAS | unverified |
| `Set_Phas_Rang` | `PHASe:RANGe <value>` | DEG90 · DEG180 · DEG270 | PHAS | unverified |
| `Set_Phas_Spe` | `PHASe:SPEed <value>` | FAST · MED · SLOW | PHAS | unverified |
| `Set_Phas_Step` | `PHASe:STEPs <value>` | integer | PHAS | unverified |
| `Set_Phas_Swpt` | `PHASe:SWPType <value>` | FREQ · AMPL | PHAS | unverified |
| `Set_Phas_Unit` | `PHASe:UNIT <value>` | DEG | PHAS | unverified |
| `Set_Rat_Amax` | `:RAT:AMAX <value>` | numeric | RAT | unverified |
| `Set_Rat_Amin` | `RATio:AMIN <value>` | numeric | RAT | unverified |
| `Set_Rat_Ext` | `RATio:EXTernal <value>` | OFF · ON | RAT | unverified |
| `Set_Rat_Fmax` | `RATio:FMAX <value>` | numeric | RAT | unverified |
| `Set_Rat_Fmin` | `RATio:FMIN <value>` | numeric | RAT | unverified |
| `Set_Rat_Lun` | `RATio:LUNit <value>` | V · DBV · DBU · DBM · DBR · DBG · W · OFF | RAT | unverified |
| `Set_Rat_Mmax` | `RATio:MMAX <value>` | numeric | RAT | unverified |
| `Set_Rat_Mmin` | `RATio:MMIN <value>` | numeric | RAT | unverified |
| `Set_Rat_Mode` | `RATio:MODE <value>` | enum | RAT | unverified |
| `Set_Rat_Spe` | `RATio:SPEed <value>` | FAST · MED · SLOW | RAT | unverified |
| `Set_Rat_Step` | `RATio:STEPs <value>` | integer | RAT | unverified |
| `Set_Rat_Swpt` | `RATio:SWPType <value>` | FREQ · AMPL | RAT | unverified |
| `Set_Rat_Unit` | `RATio:UNIT <value>` | DB | RAT | unverified |
| `Set_Sin_Hpas` | `:SIN:HPAS <value>` | ON · OFF | SIN | unverified |
| `Set_Sin_Lpas` | `SINad:LPASs <value>` | R22 · Q22 · R30 · R80 · R300 | SIN | unverified |
| `Set_Sin_Lun` | `SINad:LUNit <value>` | V · DBV · DBU · DBM · DBR · DBG · W · OFF | SIN | unverified |
| `Set_Sin_Mmax` | `SINad:MMAX <value>` | numeric | SIN | unverified |
| `Set_Sin_Mmin` | `SINad:MMIN <value>` | numeric | SIN | unverified |
| `Set_Sin_Notc` | `SINad:NOTChfreq <value>` | unknown | SIN | unverified |
| `Set_Sin_Pres` | `SINad:PRESet <value>` | F400 · F1000 | SIN | unverified |
| `Set_Sin_Tun` | `SINad:TUNe <value>` | GENT · FIXT · OFF | SIN | unverified |
| `Set_Sin_Unit` | `SINad:UNIT <value>` | DB | SIN | unverified |
| `Set_Thd_Amax` | `:THD:AMAX <value>` | numeric | THD | unverified |
| `Set_Thd_Amin` | `THD:AMIN <value>` | numeric | THD | unverified |
| `Set_Thd_Ext` | `THD:EXTernal <value>` | OFF · ON | THD | unverified |
| `Set_Thd_Filt` | `THD:FILTer <value>` | WTD · UNWT · AVER | THD | unverified |
| `Set_Thd_Fmax` | `THD:FMAX <value>` | numeric | THD | unverified |
| `Set_Thd_Fmin` | `THD:FMIN <value>` | numeric | THD | unverified |
| `Set_Thd_Hpas` | `THD:HPASs <value>` | ON · OFF | THD | unverified |
| `Set_Thd_Lpas` | `THD:LPASs <value>` | R22 · Q22 · R30 · R80 · R300 | THD | unverified |
| `Set_Thd_Lun` | `THD:LUNit <value>` | V · DBV · DBU · DBM · DBR · DBG · W · OFF | THD | unverified |
| `Set_Thd_Mmax` | `THD:MMAX <value>` | numeric | THD | unverified |
| `Set_Thd_Mmin` | `THD:MMIN <value>` | numeric | THD | unverified |
| `Set_Thd_Notc` | `THD:NOTChfreq <value>` | unknown | THD | unverified |
| `Set_Thd_Spe` | `THD:SPEed <value>` | FAST · MED · SLOW | THD | unverified |
| `Set_Thd_Step` | `THD:STEPs <value>` | integer | THD | unverified |
| `Set_Thd_Swpt` | `THD:SWPType <value>` | FREQ · AMPL | THD | unverified |
| `Set_Thd_Tun` | `THD:TUNe <value>` | AUT · GENT · FIXT | THD | unverified |
| `Set_Thd_Unit` | `THD:UNIT <value>` | PCT · DB · V · DBV · DBU · DBM · DBR | THD | unverified |
| `Set_Thd_Wtd` | `THD:WTD <value>` | unknown | THD | unverified |
| `Set_Wf_Det` | `:WF:DET <value>` | IEC · NAB · JIS | WF | unverified |
| `Set_Wf_Filt` | `WF:FILTer <value>` | WTD · UNWT | WF | unverified |
| `Set_Wf_Lun` | `WF:LUNit <value>` | V · DBV · DBU · DBM · DBR · DBG · W · OFF | WF | unverified |
| `Set_Wf_Mmax` | `WF:MMAX <value>` | numeric | WF | unverified |
| `Set_Wf_Mmin` | `WF:MMIN <value>` | numeric | WF | unverified |
| `Set_Wf_Resp` | `WF:RESPonse <value>` | PEAK · SIG2 | WF | unverified |
| `Set_Wf_Unit` | `WF:UNIT <value>` | PCT | WF | unverified |
| `Set_Wf_Wfun` | `WF:WFUNit <value>` | HZ · DPCT3000 · DPCT3150 · OFF | WF | unverified |
| `Set_Xtal_Amax` | `:XTAL:AMAX <value>` | numeric | XTAL | unverified |
| `Set_Xtal_Amin` | `XTALk:AMIN <value>` | numeric | XTAL | unverified |
| `Set_Xtal_Ext` | `XTALk:EXTernal <value>` | OFF · ON | XTAL | unverified |
| `Set_Xtal_Fmax` | `XTALk:FMAX <value>` | numeric | XTAL | unverified |
| `Set_Xtal_Fmin` | `XTALk:FMIN <value>` | numeric | XTAL | unverified |
| `Set_Xtal_Lun` | `XTALk:LUNit <value>` | V · DBV · DBU · DBM · DBR · DBG · W · OFF | XTAL | unverified |
| `Set_Xtal_Mmax` | `XTALk:MMAX <value>` | numeric | XTAL | unverified |
| `Set_Xtal_Mmin` | `XTALk:MMIN <value>` | numeric | XTAL | unverified |
| `Set_Xtal_Spe` | `XTALk:SPEed <value>` | FAST · MED · SLOW | XTAL | unverified |
| `Set_Xtal_Step` | `XTALk:STEPs <value>` | integer | XTAL | unverified |
| `Set_Xtal_Swpt` | `XTALk:SWPType <value>` | FREQ · AMPL | XTAL | unverified |
| `Set_Xtal_Unit` | `XTALk:UNIT <value>` | V · DBV · DBU · DBM · DBR · DB | XTAL | unverified |

## `nab` — reads more than one thing (observation, telemetry) (289)

| Command | SCPI | Argument | Group | |
|---|---|---|---|---|
| `Get_Acm_Lun` | `ACMains:LUNit?` |  | ACM | unverified |
| `Get_Acm_Mmax` | `ACMains:MMAX?` |  | ACM | unverified |
| `Get_Acm_Mmin` | `ACMains:MMIN?` |  | ACM | unverified |
| `Get_Acm_Unit` | `ACMains:UNIT?` |  | ACM | unverified |
| `Get_Ampl_Amax` | `AMPLitude:AMAX?` |  | AMPL | unverified |
| `Get_Ampl_Amin` | `AMPLitude:AMIN?` |  | AMPL | unverified |
| `Get_Ampl_Bpfr` | `AMPLitude:BPFR?` |  | AMPL | unverified |
| `Get_Ampl_Ext` | `AMPLitude:EXTernal?` |  | AMPL | unverified |
| `Get_Ampl_Filt` | `AMPLitude:FILTer?` |  | AMPL | unverified |
| `Get_Ampl_Fmax` | `AMPLitude:FMAX?` |  | AMPL | unverified |
| `Get_Ampl_Fmin` | `AMPLitude:FMIN?` |  | AMPL | unverified |
| `Get_Ampl_Hpas` | `AMPLitude:HPASs?` |  | AMPL | unverified |
| `Get_Ampl_Lpas` | `AMPLitude:LPASs?` |  | AMPL | unverified |
| `Get_Ampl_Mmax` | `AMPLitude:MMAX?` |  | AMPL | unverified |
| `Get_Ampl_Mmin` | `AMPLitude:MMIN?` |  | AMPL | unverified |
| `Get_Ampl_Spe` | `AMPLitude:SPEed?` |  | AMPL | unverified |
| `Get_Ampl_Steps` | `AMPLitude:STEPS?` |  | AMPL | unverified |
| `Get_Ampl_Swpt` | `AMPLitude:SWPType?` |  | AMPL | unverified |
| `Get_Ampl_Unit` | `AMPLitude:UNIT?` |  | AMPL | unverified |
| `Get_Ampl_Wtd` | `AMPLitude:WTD?` |  | AMPL | unverified |
| `Get_Damp_Amax` | `DAMPlitude:AMAX?` |  | DAMP | unverified |
| `Get_Damp_Amin` | `DAMPlitude:AMIN?` |  | DAMP | unverified |
| `Get_Damp_Bpfr` | `DAMPlitude:BPFR?` |  | DAMP | unverified |
| `Get_Damp_Ext` | `DAMPlitude:EXTernal?` |  | DAMP | unverified |
| `Get_Damp_Filt` | `DAMPlitude:FILTer?` |  | DAMP | unverified |
| `Get_Damp_Fmax` | `DAMPlitude:FMAX?` |  | DAMP | unverified |
| `Get_Damp_Fmin` | `DAMPlitude:FMIN?` |  | DAMP | unverified |
| `Get_Damp_Hpas` | `DAMPlitude:HPASs?` |  | DAMP | unverified |
| `Get_Damp_Lpas` | `DAMPlitude:LPASs?` |  | DAMP | unverified |
| `Get_Damp_Mmax` | `DAMPlitude:MMAX?` |  | DAMP | unverified |
| `Get_Damp_Mmin` | `DAMPlitude:MMIN?` |  | DAMP | unverified |
| `Get_Damp_Spe` | `DAMPlitude:SPEed?` |  | DAMP | unverified |
| `Get_Damp_Step` | `DAMPlitude:STEPs?` |  | DAMP | unverified |
| `Get_Damp_Swpt` | `DAMPlitude:SWPType?` |  | DAMP | unverified |
| `Get_Damp_Unit` | `DAMPlitude:UNIT?` |  | DAMP | unverified |
| `Get_Damp_Wtd` | `DAMPlitude:WTD?` |  | DAMP | unverified |
| `Get_Dchk_Bits` | `DCHK:BITS?` |  | DCHK | unverified |
| `Get_Dchk_Dbit` | `DCHK:DBITs?` |  | DCHK | unverified |
| `Get_Dchk_Dun` | `DCHK:DUNit?` |  | DCHK | unverified |
| `Get_Dchk_Mmax` | `DCHK:MMAX?` |  | DCHK | unverified |
| `Get_Dchk_Mmin` | `DCHK:MMIN?` |  | DCHK | unverified |
| `Get_Dchk_Unit` | `DCHK:UNIT?` |  | DCHK | unverified |
| `Get_Dimd_Amax` | `DIMD:AMAX?` |  | DIMD | unverified |
| `Get_Dimd_Amin` | `DIMD:AMIN?` |  | DIMD | unverified |
| `Get_Dimd_Lun` | `DIMD:LUNit?` |  | DIMD | unverified |
| `Get_Dimd_Mmax` | `DIMD:MMAX?` |  | DIMD | unverified |
| `Get_Dimd_Mmin` | `DIMD:MMIN?` |  | DIMD | unverified |
| `Get_Dimd_Spe` | `DIMD:SPEed?` |  | DIMD | unverified |
| `Get_Dimd_Step` | `DIMD:STEPs?` |  | DIMD | unverified |
| `Get_Dimd_Unit` | `DIMD:UNIT?` |  | DIMD | unverified |
| `Get_Dio_Ddref` | `DIO:DDREF?` |  | DIO | unverified |
| `Get_Dio_Dir` | `DIO:DIResolution?` |  | DIO | unverified |
| `Get_Dio_Dref` | `DIO:DREF?` |  | DIO | unverified |
| `Get_Dio_Dun` | `DIO:DUNit?` |  | DIO | unverified |
| `Get_Dio_Frqr` | `DIO:FRQRef?` |  | DIO | unverified |
| `Get_Dio_Mmax` | `DIO:MMAX?` |  | DIO | unverified |
| `Get_Dio_Mmin` | `DIO:MMIN?` |  | DIO | unverified |
| `Get_Dio_Unit` | `DIO:UNIT?` |  | DIO | unverified |
| `Get_Dist_Cod` | `DISTatus:CODing?` |  | DIST | unverified |
| `Get_Dist_Con` | `DISTatus:CONfidence?` |  | DIST | unverified |
| `Get_Dist_Err` | `DISTatus:ERRor?` |  | DIST | unverified |
| `Get_Dist_Inv` | `DISTatus:INValid?` |  | DIST | unverified |
| `Get_Dist_Lock` | `DISTatus:LOCK?` |  | DIST | unverified |
| `Get_Dist_Par` | `DISTatus:PARity?` |  | DIST | unverified |
| `Get_Dist_Stat` | `DISTatus:STATus?` |  | DIST | unverified |
| `Get_Dist_Std` | `:DISTatus:STD?` |  | DIST | unverified |
| `Get_Djit_Amax` | `DJITter:AMAX?` |  | DJIT | unverified |
| `Get_Djit_Amin` | `DJITter:AMIN?` |  | DJIT | unverified |
| `Get_Djit_Bpfr` | `DJITter:BPFR?` |  | DJIT | unverified |
| `Get_Djit_Det` | `DJITter:DETector?` |  | DJIT | unverified |
| `Get_Djit_Ext` | `DJITter:EXTernal?` |  | DJIT | unverified |
| `Get_Djit_Filt` | `DJITter:FILTer?` |  | DJIT | unverified |
| `Get_Djit_Fmax` | `DJITter:FMAX?` |  | DJIT | unverified |
| `Get_Djit_Fmin` | `DJITter:FMIN?` |  | DJIT | unverified |
| `Get_Djit_Hpas` | `DJITter:HPASs?` |  | DJIT | unverified |
| `Get_Djit_Jdet` | `DJITter:JDETector?` |  | DJIT | unverified |
| `Get_Djit_Mmax` | `DJITter:MMAX?` |  | DJIT | unverified |
| `Get_Djit_Mmin` | `DJITter:MMIN?` |  | DJIT | unverified |
| `Get_Djit_Spe` | `DJITter:SPEed?` |  | DJIT | unverified |
| `Get_Djit_Step` | `DJITter:STEPs?` |  | DJIT | unverified |
| `Get_Djit_Swpt` | `DJITter:SWPType?` |  | DJIT | unverified |
| `Get_Djit_Unit` | `DJITter:UNIT?` |  | DJIT | unverified |
| `Get_Dlev_Amax` | `DLEVel:AMAX?` |  | DLEV | unverified |
| `Get_Dlev_Amin` | `DLEVel:AMIN?` |  | DLEV | unverified |
| `Get_Dlev_Ext` | `DLEVel:EXTernal?` |  | DLEV | unverified |
| `Get_Dlev_Fmax` | `DLEVel:FMAX?` |  | DLEV | unverified |
| `Get_Dlev_Fmin` | `DLEVel:FMIN?` |  | DLEV | unverified |
| `Get_Dlev_Lun` | `DLEVel:LUNit?` |  | DLEV | unverified |
| `Get_Dlev_Mmax` | `DLEVel:MMAX?` |  | DLEV | unverified |
| `Get_Dlev_Mmin` | `DLEVel:MMIN?` |  | DLEV | unverified |
| `Get_Dlev_Spe` | `DLEVel:SPEed?` |  | DLEV | unverified |
| `Get_Dlev_Step` | `DLEVel:STEPs?` |  | DLEV | unverified |
| `Get_Dlev_Swpt` | `DLEVel:SWPType?` |  | DLEV | unverified |
| `Get_Dlev_Unit` | `DLEVel:UNIT?` |  | DLEV | unverified |
| `Get_Dno_Amax` | `DNOise:AMAX?` |  | DNO | unverified |
| `Get_Dno_Amin` | `DNOise:AMIN?` |  | DNO | unverified |
| `Get_Dno_Bpfr` | `DNOise:BPFR?` |  | DNO | unverified |
| `Get_Dno_Ext` | `DNOise:EXTernal?` |  | DNO | unverified |
| `Get_Dno_Filt` | `DNOise:FILTer?` |  | DNO | unverified |
| `Get_Dno_Fmax` | `DNOise:FMAX?` |  | DNO | unverified |
| `Get_Dno_Fmin` | `DNOise:FMIN?` |  | DNO | unverified |
| `Get_Dno_Hpas` | `DNOise:HPASs?` |  | DNO | unverified |
| `Get_Dno_Lpas` | `DNOise:LPASs?` |  | DNO | unverified |
| `Get_Dno_Mmax` | `DNOise:MMAX?` |  | DNO | unverified |
| `Get_Dno_Mmin` | `DNOise:MMIN?` |  | DNO | unverified |
| `Get_Dno_Spe` | `DNOise:SPEed?` |  | DNO | unverified |
| `Get_Dno_Step` | `DNOise:STEPs?` |  | DNO | unverified |
| `Get_Dno_Swpt` | `DNOise:SWPType?` |  | DNO | unverified |
| `Get_Dno_Unit` | `DNOise:UNIT?` |  | DNO | unverified |
| `Get_Dno_Wtd` | `DNOise:WTD?` |  | DNO | unverified |
| `Get_Dost_Cons` | `:DOSTatus:CONS?` |  | DOST | unverified |
| `Get_Dost_Prof` | `:DOSTatus:PROF?` |  | DOST | unverified |
| `Get_Dost_Stdo` | `:DOSTatus:STDO?` |  | DOST | unverified |
| `Get_Dost_Val` | `DOSTatus:VALidity?` |  | DOST | unverified |
| `Get_Dph_Amax` | `DPHase:AMAX?` |  | DPH | unverified |
| `Get_Dph_Amin` | `DPHase:AMIN?` |  | DPH | unverified |
| `Get_Dph_Ext` | `DPHase:EXTernal?` |  | DPH | unverified |
| `Get_Dph_Fmax` | `DPHase:FMAX?` |  | DPH | unverified |
| `Get_Dph_Fmin` | `DPHase:FMIN?` |  | DPH | unverified |
| `Get_Dph_Lun` | `DPHase:LUNit?` |  | DPH | unverified |
| `Get_Dph_Mmax` | `DPHase:MMAX?` |  | DPH | unverified |
| `Get_Dph_Mmin` | `DPHase:MMIN?` |  | DPH | unverified |
| `Get_Dph_Rang` | `DPHase:RANGe?` |  | DPH | unverified |
| `Get_Dph_Spe` | `DPHase:SPEed?` |  | DPH | unverified |
| `Get_Dph_Step` | `DPHase:STEPs?` |  | DPH | unverified |
| `Get_Dph_Swpt` | `DPHase:SWPType?` |  | DPH | unverified |
| `Get_Dph_Unit` | `DPHase:UNIT?` |  | DPH | unverified |
| `Get_Drat_Amax` | `DRATio:AMAX?` |  | DRAT | unverified |
| `Get_Drat_Amin` | `DRATio:AMIN?` |  | DRAT | unverified |
| `Get_Drat_Ext` | `DRATio:EXTernal?` |  | DRAT | unverified |
| `Get_Drat_Fmax` | `DRATio:FMAX?` |  | DRAT | unverified |
| `Get_Drat_Fmin` | `DRATio:FMIN?` |  | DRAT | unverified |
| `Get_Drat_Lun` | `DRATio:LUNit?` |  | DRAT | unverified |
| `Get_Drat_Mmax` | `DRATio:MMAX?` |  | DRAT | unverified |
| `Get_Drat_Mmin` | `DRATio:MMIN?` |  | DRAT | unverified |
| `Get_Drat_Spe` | `DRATio:SPEed?` |  | DRAT | unverified |
| `Get_Drat_Step` | `DRATio:STEPs?` |  | DRAT | unverified |
| `Get_Drat_Swpt` | `DRATio:SWPType?` |  | DRAT | unverified |
| `Get_Drat_Unit` | `DRATio:UNIT?` |  | DRAT | unverified |
| `Get_Dthd_Amax` | `DTHD:AMAX?` |  | DTHD | unverified |
| `Get_Dthd_Amin` | `DTHD:AMIN?` |  | DTHD | unverified |
| `Get_Dthd_Ext` | `DTHD:EXTernal?` |  | DTHD | unverified |
| `Get_Dthd_Filt` | `DTHD:FILTer?` |  | DTHD | unverified |
| `Get_Dthd_Fmax` | `DTHD:FMAX?` |  | DTHD | unverified |
| `Get_Dthd_Fmin` | `DTHD:FMIN?` |  | DTHD | unverified |
| `Get_Dthd_Hpas` | `DTHD:HPASs?` |  | DTHD | unverified |
| `Get_Dthd_Lpas` | `DTHD:LPASs?` |  | DTHD | unverified |
| `Get_Dthd_Lun` | `DTHD:LUNit?` |  | DTHD | unverified |
| `Get_Dthd_Mmax` | `DTHD:MMAX?` |  | DTHD | unverified |
| `Get_Dthd_Mmin` | `DTHD:MMIN?` |  | DTHD | unverified |
| `Get_Dthd_Notc` | `DTHD:NOTChfreq?` |  | DTHD | unverified |
| `Get_Dthd_Spe` | `DTHD:SPEed?` |  | DTHD | unverified |
| `Get_Dthd_Step` | `DTHD:STEP?` |  | DTHD | unverified |
| `Get_Dthd_Swpt` | `DTHD:SWPType?` |  | DTHD | unverified |
| `Get_Dthd_Tun` | `DTHD:TUNe?` |  | DTHD | unverified |
| `Get_Dthd_Unit` | `DTHD:UNIT?` |  | DTHD | unverified |
| `Get_Dthd_Wtd` | `DTHD:WTD?` |  | DTHD | unverified |
| `Get_Dxt_Amax` | `DXTalk:AMAX?` |  | DXT | unverified |
| `Get_Dxt_Amin` | `DXTalk:AMIN?` |  | DXT | unverified |
| `Get_Dxt_Ext` | `DXTalk:EXTernal?` |  | DXT | unverified |
| `Get_Dxt_Fmax` | `DXTalk:FMAX?` |  | DXT | unverified |
| `Get_Dxt_Fmin` | `DXTalk:FMIN?` |  | DXT | unverified |
| `Get_Dxt_Lun` | `DXTalk:LUNit?` |  | DXT | unverified |
| `Get_Dxt_Mmax` | `DXTalk:MMAX?` |  | DXT | unverified |
| `Get_Dxt_Mmin` | `DXTalk:MMIN?` |  | DXT | unverified |
| `Get_Dxt_Spe` | `DXTalk:SPEed?` |  | DXT | unverified |
| `Get_Dxt_Step` | `DXTalk:STEPs?` |  | DXT | unverified |
| `Get_Dxt_Swpt` | `DXTalk:SWPType?` |  | DXT | unverified |
| `Get_Dxt_Unit` | `DXTalk:UNIT?` |  | DXT | unverified |
| `Get_Genl_Fmax` | `GENLoad:FMAX?` |  | GENL | unverified |
| `Get_Genl_Fmin` | `GENLoad:FMIN?` |  | GENL | unverified |
| `Get_Genl_Mmax` | `GENLoad:MMAX?` |  | GENL | unverified |
| `Get_Genl_Mmin` | `GENLoad:MMIN?` |  | GENL | unverified |
| `Get_Genl_Spe` | `GENLoad:SPEed?` |  | GENL | unverified |
| `Get_Genl_Step` | `GENLoad:STEPs?` |  | GENL | unverified |
| `Get_Genl_Unit` | `GENLoad:UNIT?` |  | GENL | unverified |
| `Get_Imd_Amax` | `IMD:AMAX?` |  | IMD | unverified |
| `Get_Imd_Amin` | `IMD:AMIN?` |  | IMD | unverified |
| `Get_Imd_Lun` | `IMD:LUNit?` |  | IMD | unverified |
| `Get_Imd_Mmax` | `IMD:MMAX?` |  | IMD | unverified |
| `Get_Imd_Mmin` | `IMD:MMIN?` |  | IMD | unverified |
| `Get_Imd_Spe` | `IMD:SPEed?` |  | IMD | unverified |
| `Get_Imd_Steps` | `IMD:STEPS?` |  | IMD | unverified |
| `Get_Imd_Unit` | `IMD:UNIT?` |  | IMD | unverified |
| `Get_Lev_Amax` | `LEVel:AMAX?` |  | LEV | unverified |
| `Get_Lev_Amin` | `LEVel:AMIN?` |  | LEV | unverified |
| `Get_Lev_Ext` | `LEVel:EXTernal?` |  | LEV | unverified |
| `Get_Lev_Fmax` | `LEVel:FMAX?` |  | LEV | unverified |
| `Get_Lev_Fmin` | `LEVel:FMIN?` |  | LEV | unverified |
| `Get_Lev_Lun` | `LEVel:LUNit?` |  | LEV | unverified |
| `Get_Lev_Mmax` | `LEVel:MMAX?` |  | LEV | unverified |
| `Get_Lev_Mmin` | `LEVel:MMIN?` |  | LEV | unverified |
| `Get_Lev_Spe` | `LEVel:SPEed?` |  | LEV | unverified |
| `Get_Lev_Step` | `LEVel:STEPs?` |  | LEV | unverified |
| `Get_Lev_Swpt` | `LEVel:SWPType?` |  | LEV | unverified |
| `Get_Lev_Unit` | `LEVel:UNIT?` |  | LEV | unverified |
| `Read_Ch_A_Only` | `M1?` |  | Read Commands |  |
| `Read_Stereo_AB` | `M1?;M2?` |  | Read Commands |  |
| `Read_Ch_B_Only` | `M2?` |  | Read Commands |  |
| `Get_Nois_Amax` | `NOISe:AMAX?` |  | NOIS | unverified |
| `Get_Nois_Amin` | `NOISe:AMIN?` |  | NOIS | unverified |
| `Get_Nois_Bpfr` | `NOISe:BPFR?` |  | NOIS | unverified |
| `Get_Nois_Ext` | `NOISe:EXTernal?` |  | NOIS | unverified |
| `Get_Nois_Filt` | `NOISe:FILTer?` |  | NOIS | unverified |
| `Get_Nois_Fmax` | `NOISe:FMAX?` |  | NOIS | unverified |
| `Get_Nois_Fmin` | `NOISe:FMIN?` |  | NOIS | unverified |
| `Get_Nois_Hpas` | `NOISe:HPASs?` |  | NOIS | unverified |
| `Get_Nois_Lpas` | `NOISe:LPASs?` |  | NOIS | unverified |
| `Get_Nois_Mmax` | `NOISe:MMAX?` |  | NOIS | unverified |
| `Get_Nois_Mmin` | `NOISe:MMIN?` |  | NOIS | unverified |
| `Get_Nois_Spe` | `NOISe:SPEed?` |  | NOIS | unverified |
| `Get_Nois_Step` | `NOISe:STEPs?` |  | NOIS | unverified |
| `Get_Nois_Swpt` | `NOISe:SWPType?` |  | NOIS | unverified |
| `Get_Nois_Unit` | `NOISe:UNIT?` |  | NOIS | unverified |
| `Get_Nois_Wtd` | `NOISe:WTD?` |  | NOIS | unverified |
| `Get_Phas_Amax` | `PHASe:AMAX?` |  | PHAS | unverified |
| `Get_Phas_Amin` | `PHASe:AMIN?` |  | PHAS | unverified |
| `Get_Phas_Ave` | `PHASe:AVErage?` |  | PHAS | unverified |
| `Get_Phas_Ext` | `PHASe:EXTernal?` |  | PHAS | unverified |
| `Get_Phas_Fmax` | `PHASe:FMAX?` |  | PHAS | unverified |
| `Get_Phas_Fmin` | `PHASe:FMIN?` |  | PHAS | unverified |
| `Get_Phas_Lun` | `PHASe:LUNit?` |  | PHAS | unverified |
| `Get_Phas_Mmax` | `PHASe:MMAX?` |  | PHAS | unverified |
| `Get_Phas_Mmin` | `PHASe:MMIN?` |  | PHAS | unverified |
| `Get_Phas_Rang` | `PHASe:RANGe?` |  | PHAS | unverified |
| `Get_Phas_Spe` | `PHASe:SPEed?` |  | PHAS | unverified |
| `Get_Phas_Step` | `PHASe:STEPs?` |  | PHAS | unverified |
| `Get_Phas_Swpt` | `PHASe:SWPType?` |  | PHAS | unverified |
| `Get_Phas_Unit` | `PHASe:UNIT?` |  | PHAS | unverified |
| `Get_Rat_Amax` | `RATio:AMAX?` |  | RAT | unverified |
| `Get_Rat_Amin` | `RATio:AMIN?` |  | RAT | unverified |
| `Get_Rat_Ext` | `RATio:EXTernal?` |  | RAT | unverified |
| `Get_Rat_Fmax` | `RATio:FMAX?` |  | RAT | unverified |
| `Get_Rat_Fmin` | `RATio:FMIN?` |  | RAT | unverified |
| `Get_Rat_Lun` | `RATio:LUNit?` |  | RAT | unverified |
| `Get_Rat_Mmax` | `RATio:MMAX?` |  | RAT | unverified |
| `Get_Rat_Mmin` | `RATio:MMIN?` |  | RAT | unverified |
| `Get_Rat_Mode` | `RATio:MODE?` |  | RAT | unverified |
| `Get_Rat_Spe` | `RATio:SPEed?` |  | RAT | unverified |
| `Get_Rat_Step` | `RATio:STEPs?` |  | RAT | unverified |
| `Get_Rat_Swpt` | `RATio:SWPType?` |  | RAT | unverified |
| `Get_Rat_Unit` | `RATio:UNIT?` |  | RAT | unverified |
| `Get_Sin_Hpas` | `SINad:HPASs?` |  | SIN | unverified |
| `Get_Sin_Lpas` | `SINad:LPASs?` |  | SIN | unverified |
| `Get_Sin_Lun` | `SINad:LUNit?` |  | SIN | unverified |
| `Get_Sin_Mmax` | `SINad:MMAX?` |  | SIN | unverified |
| `Get_Sin_Mmin` | `SINad:MMIN?` |  | SIN | unverified |
| `Get_Sin_Notc` | `SINad:NOTChfreq?` |  | SIN | unverified |
| `Get_Sin_Pres` | `SINad:PRESet?` |  | SIN | unverified |
| `Get_Sin_Tun` | `SINad:TUNe?` |  | SIN | unverified |
| `Get_Sin_Unit` | `SINad:UNIT?` |  | SIN | unverified |
| `Get_Thd_Amax` | `THD:AMAX?` |  | THD | unverified |
| `Get_Thd_Amin` | `THD:AMIN?` |  | THD | unverified |
| `Get_Thd_Ext` | `THD:EXTernal?` |  | THD | unverified |
| `Get_Thd_Filt` | `THD:FILTer?` |  | THD | unverified |
| `Get_Thd_Fmax` | `THD:FMAX?` |  | THD | unverified |
| `Get_Thd_Fmin` | `THD:FMIN?` |  | THD | unverified |
| `Get_Thd_Hpas` | `THD:HPASs?` |  | THD | unverified |
| `Get_Thd_Lpas` | `THD:LPASs?` |  | THD | unverified |
| `Get_Thd_Lun` | `THD:LUNit?` |  | THD | unverified |
| `Get_Thd_Mmax` | `THD:MMAX?` |  | THD | unverified |
| `Get_Thd_Mmin` | `THD:MMIN?` |  | THD | unverified |
| `Get_Thd_Notc` | `THD:NOTChfreq?` |  | THD | unverified |
| `Get_Thd_Spe` | `THD:SPEed?` |  | THD | unverified |
| `Get_Thd_Step` | `THD:STEPs?` |  | THD | unverified |
| `Get_Thd_Swpt` | `THD:SWPType?` |  | THD | unverified |
| `Get_Thd_Tun` | `THD:TUNe?` |  | THD | unverified |
| `Get_Thd_Unit` | `THD:UNIT?` |  | THD | unverified |
| `Get_Thd_Wtd` | `THD:WTD?` |  | THD | unverified |
| `Get_Wf_Det` | `WF:DETector?` |  | WF | unverified |
| `Get_Wf_Filt` | `WF:FILTer?` |  | WF | unverified |
| `Get_Wf_Lun` | `WF:LUNit?` |  | WF | unverified |
| `Get_Wf_Mmax` | `WF:MMAX?` |  | WF | unverified |
| `Get_Wf_Mmin` | `WF:MMIN?` |  | WF | unverified |
| `Get_Wf_Resp` | `WF:RESPonse?` |  | WF | unverified |
| `Get_Wf_Unit` | `WF:UNIT?` |  | WF | unverified |
| `Get_Wf_Wfun` | `WF:WFUNit?` |  | WF | unverified |
| `Get_Xtal_Amax` | `XTALk:AMAX?` |  | XTAL | unverified |
| `Get_Xtal_Amin` | `XTALk:AMIN?` |  | XTAL | unverified |
| `Get_Xtal_Ext` | `XTALk:EXTernal?` |  | XTAL | unverified |
| `Get_Xtal_Fmax` | `XTALk:FMAX?` |  | XTAL | unverified |
| `Get_Xtal_Fmin` | `XTALk:FMIN?` |  | XTAL | unverified |
| `Get_Xtal_Lun` | `XTALk:LUNit?` |  | XTAL | unverified |
| `Get_Xtal_Mmax` | `XTALk:MMAX?` |  | XTAL | unverified |
| `Get_Xtal_Mmin` | `XTALk:MMIN?` |  | XTAL | unverified |
| `Get_Xtal_Spe` | `XTALk:SPEed?` |  | XTAL | unverified |
| `Get_Xtal_Step` | `XTALk:STEPs?` |  | XTAL | unverified |
| `Get_Xtal_Swpt` | `XTALk:SWPType?` |  | XTAL | unverified |
| `Get_Xtal_Unit` | `XTALk:UNIT?` |  | XTAL | unverified |

## `do` — executes an action; takes no value (45)

| Command | SCPI | Argument | Group | |
|---|---|---|---|---|
| `Do_Clear_Status` | `*CLS` |  | Global Utilities |  |
| `Reset_Device` | `*RST` |  | Global Utilities |  |
| `Do_Ampl_Step` | `AMPLitude:STEPs` |  | AMPL | unverified |
| `Do_At_Fmax` | `ATio:FMAX` |  | AT | unverified |
| `Set_Unit_dBm` | `:AUNits DBM` |  | Select Output Unit (M1/M2) |  |
| `Set_Unit_dBu` | `:AUNits DBU` |  | Select Output Unit (M1/M2) |  |
| `Set_Unit_dBV` | `:AUNits DBV` |  | Select Output Unit (M1/M2) |  |
| `Set_Unit_Volts` | `:AUNits V` |  | Select Output Unit (M1/M2) |  |
| `Set_Unit_Watts` | `:AUNits W` |  | Select Output Unit (M1/M2) |  |
| `Do_Dimd_Ext` | `DIMD:EXTernal` |  | DIMD | unverified |
| `Do_Dimd_Fmax` | `DIMD:FMAX` |  | DIMD | unverified |
| `Do_Dimd_Fmin` | `DIMD:FMIN` |  | DIMD | unverified |
| `Select_DIN_BNC` | `:DINPut BNC` |  | Select Digital Input Connector |  |
| `Select_DIN_Generator` | `:DINPut GENerator` |  | Select Digital Input Connector |  |
| `Select_DIN_Optical` | `:DINPut OPTical` |  | Select Digital Input Connector |  |
| `Select_DIN_XLR` | `:DINPut XLR` |  | Select Digital Input Connector |  |
| `Do_Display_Panel` | `:DISPlay PANel` |  | Global Utilities |  |
| `Do_Dlev_Fm` | `DLEVel:FMin` |  | DLEV | unverified |
| `Set_DOUT_OFF` | `:DOUTput OFF` |  | Digital Output State |  |
| `Set_DOUT_ON` | `:DOUTput ON` |  | Digital Output State |  |
| `Do_Dthd_Medium` | `DTHD:MEDIUM` |  | DTHD | unverified |
| `Mode_Amplitude` | `:FUNCtion AMPLitude` |  | Select Measurement Mode |  |
| `Mode_Level_Stereo` | `:FUNCtion LEVel` |  | Select Measurement Mode |  |
| `Mode_Noise` | `:FUNCtion NOISE` |  | Select Measurement Mode |  |
| `Mode_Phase` | `:FUNCtion PHASE` |  | Select Measurement Mode |  |
| `Mode_SINAD` | `:FUNCtion SINad` |  | Select Measurement Mode |  |
| `Mode_THD_N` | `:FUNCtion THD` |  | Select Measurement Mode |  |
| `Mode_Crosstalk` | `:FUNCtion XTALK` |  | Select Measurement Mode |  |
| `Do_Gen_Dig` | `GEN:DIG` |  | GEN | unverified |
| `Do_Gen_Jitt` | `GEN:JITT` |  | GEN | unverified |
| `Do_Imd_Ext` | `IMD:EXTernal` |  | IMD | unverified |
| `Do_Imd_Step` | `IMD:STEPs` |  | IMD | unverified |
| `Select_Input_Analog_A` | `:INPut A` |  | Route signals to Analyzer A |  |
| `Select_Input_Analog_B` | `:INPut B` |  | Route signals to Analyzer B |  |
| `Select_Input_Gen_Monitor_A` | `:INPut GENA` |  | Route signals to Analyzer A |  |
| `Select_Input_Gen_Monitor_B` | `:INPut GENB` |  | Route signals to Analyzer B |  |
| `Do_Lev_Fm` | `LEVel:FMin` |  | LEV | unverified |
| `Do_Output_OFF` | `:OUTPut OFF` |  | Master Generator Output |  |
| `Do_Output_ON` | `:OUTPut ON` |  | Master Generator Output |  |
| `Do_Phas_Aver` | `PHASe:AVERage` |  | PHAS | unverified |
| `Do_Ref_Watt` | `REF:WATT` |  | REF | unverified |
| `Do_Thd_Medium` | `THD:MEDIUM` |  | THD | unverified |
| `Set_Wave_IMD` | `:WAVeform IMD` |  | Select Waveform Shape |  |
| `Set_Wave_Sine` | `:WAVeform SINE` |  | Select Waveform Shape |  |
| `Set_Wave_Square` | `:WAVeform SQUare` |  | Select Waveform Shape |  |

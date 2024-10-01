## ZPL Commands

| Command | Format | Description |
| ------- | ------ | ----------- |
| ^A | ^Afo,h,w,d:f.x | Use Scalable/Bitmapped Font |
| ^A@ | ^A@o,h,w,d:f.x | Use Font Name to Call Font |
| ^B0 | ^B0a,b,c,d,e,f,g | Aztec Bar Code Parameters |
| ^B1 | ^B1o,e,h,f,g | Code 11 Bar Code |
| ^B2 | ^B2o,h,f,g,e,j | Interleaved 2 of 5 Bar Code |
| ^B3 | ^B3o,e,h,f,g | Code 39 Bar Code |
| ^B4 | ^B4o,h,f,m | Code 49 Bar Code |
| ^B5 | ^B5o,h,f,g | Planet Code bar code |
| ^B7 | ^B7o,h,s,c,r,t | PDF417 Bar Code |
| ^B8 | ^B8o,h,f,g | EAN-8 Bar Code |
| ^B9 | ^B9,h,f,g,e | UPC-E Bar Code |
| ^BA | ^BAo,h,f,g,e | Code 93 Bar Code |
| ^BB | ^BBo,h,s,c,r,m | CODABLOCK Bar Code |
| ^BC | ^BCo,h,f,g,e,m | Code 128 Bar Code (Subsets A, B, and C) |
| ^BD | ^BDm,n,t | UPS MaxiCode Bar Code |
| ^BE | ^BEo,h,f,g | EAN-13 Bar Code |
| ^BF | ^BFo,h,m | MicroPDF417 Bar Code |
| ^BI | ^BIo,h,f,g | Industrial 2 of 5 Bar Codes |
| ^BJ | ^BJo,h,f,g | Standard 2 of 5 Bar Code |
| ^BK | ^BKo,e,h,f,g,k,l | ANSI Codabar Bar Code |
| ^BL | ^BLo,h,g | LOGMARS Bar Code |
| ^BM | ^BMo,e,h,f,g,e2 | MSI Bar Code |
| ^BO | ^BOa,b,c,d,e,f,g | Aztec Bar Code Parameters |
| ^BP | ^BPo,e,h,f,g | Plessey Bar Code |
| ^BQ | ^BQa,b,c,d,e | QR Code Bar Code |
| ^BR | ^BRa,b,c,d,e,f | GS1 Databar |
| ^BS | ^BSo,h,f,g | UPC/EAN Extensions |
| ^BT | ^BTo,w1,r1,h1,w2,h2 | TLC39 Bar Code |
| ^BU | ^BUo,h,f,g,e | UPC-A Bar Code |
| ^BX | ^BXo,h,s,c,r,f,g,a | Data Matrix Bar Code |
| ^BY | ^BYw,r,h | Bar Code Field Default |
| ^BZ | ^BZo,h,f,g,t | POSTAL Bar Code |
| ^CC | ^CCx or ~CCx | Change Caret (Alt. ~CC) |
| ^CD | ^CDa or ~CDa | Change Delimiter (Alt. ~CD) |
| ^CF | ^CFf,h,w | Change Alphanumeric Default Font |
| ^CI | ^CIa,s1,d1,s2,d2,... | Change International Font/Encoding |
| ^CM | ^CMa,b,c,d | Change Memory Letter Designation |
| ^CN | ^CNa | Cut Now |
| ^CO | ^COa,b,c | Cache On |
| ^CP | ^CPa | Remove Label |
| ^CT | ^CTa or ~CTa | Change Tilde (Alt. ~CT) |
| ^CV | ^CVa | Code Validation |
| ^CW | ^CWa,d:o.x | Font Identifier |
| ~DB | ~DBd:o.x,a,h,w,base,space,#char,©,data | Download Bitmap Font |
| ~DE | ~DEd:o.x,s,data | Download Encoding |
| ^DF | ^DFd:o.x | Download Format |
| ~DG | ~DGd:o.x,t,w,data | Download Graphics |
| ~DN | ~DN | Abort Download Graphic |
| ~DS | ~DSd:o.x,s,data | Download Intellifont (Scalable Font) |
| ~DT | ~DTd:o.x,s,data | Download Bounded TrueType Font |
| ~DU | ~DUd:o.x,s,data | Download Unbounded TrueType Font |
| ~DY | ~DYd:f,b,x,t,w,data | Download Objects |
| ~EG | ~EG or ^EG | Erase All Graphics (Alt. ^EG) |
| ^FB | ^FBa,b,c,d,e | Field Block |
| ^FC | ^FCa,b,c | Field Clock |
| ^FD | ^FDa | Field Data |
| ^FH | ^FHa | Field Hexadecimal Indicator |
| ^FL | ^FL<ext>,<base>,<link> | Font Linking |
| ^FM | ^FMx1,y1,x2,y2,... | Multiple Field Origin Locations |
| ^FN | ^FN#"a" | Field Number |
| ^FO | ^FOx,y,z | Field Origin |
| ^FP | ^FPd,g | Field Parameter |
| ^FR | ^FR | Field Reverse Print |
| ^FS | ^FS | Field Separator |
| ^FT | ^FTx,y,z | Field Typeset |
| ^FV | ^FVa | Field Variable |
| ^FW | ^FWr,z | Field Orientation |
| ^FX | ^FXc | Comment |
| ^GB | ^GBw,h,t,c,r | Graphic Box |
| ^GC | ^GCd,t,c | Graphic Circle |
| ^GD | ^GDw,h,t,c,o | Graphic Diagonal Line |
| ^GE | ^GEw,h,t,c | Graphic Ellipse |
| ^GF | ^GFa,b,c,d,data | Graphic Field |
| ^GS | ^GSo,h,w | Graphic Symbol |
| ~HB | ~HB | Return Battery Status |
| ~HD | ~HD | Return Head Diagnostic |
| ^HF | ^HFd,o,x | Return Host Format |
| ^HG | ^HGd:o.x | Return Host Graphic |
| ^HH | ^HH | Return Configuration Label |
| ~HI | ~HI | Return Host Identification |
| ~HM | ~HM | Return Host RAM Status |
| ~HQ | ~HQquery-type | Return Host Query |
| ~HS | ~HS | Return Host Status |
| ~HU | ~HU | Return ZebraNet Alert Configuration |
| ^HV | ^HV#,n,h,t,a | Return Host Verification |
| ^HW | ^HWd:o.x | Return Host Directory List |
| ^HY | ^HYd:o.x | Upload Graphics |
| ^HZ | ^HZb | Display Description Information |
| ^HZ | ^HZO,d:o.x,l | Display Description Information |
| ^ID | ^IDd:o.x | Object Delete |
| ^IL | ^ILd:o.x | Image Load |
| ^IM | ^IMd:o.x | Image Move |
| ^IS | ^ISd:o.x,p | Image Save |
| ~JA | ~JA | Cancel All |
| ^JB | ^JBa | Initialize Flash Memory |
| ~JB | ~JB | Reset Optional Memory |
| ~JC | ~JC | Set Media Sensor Calibration |
| ~JD | ~JD | Enable Communications Diagnostics |
| ~JE | ~JE | Disable Diagnostics |
| ~JF | ~JFp | Set Battery Condition |
| ~JG | ~JG | Graphing Sensor Calibration |
| ^JH | ^JHa,b,c,d,e,f,g,h,i,j | Early Warning Settings |
| ^JI | ^JId:o.x,b,c,d | Start Zebra BASIC Interpreter |
| ~JI | ~JI | Start Zebra BASIC Interpreter |
| ^JJ | ^JJa,b,c,d,e,f | Set Auxiliary Port |
| ~JK | ~JK | Delayed Cut |
| ~JL | ~JL | Set Label Length |
| ^JM | ^JMn | Set Dots per Millimeter |
| ~JN | ~JN | Head Test Fatal |
| ~JO | ~JO | Head Test Non-Fatal |
| ~JP | ~JP | Pause and Cancel Format |
| ~JQ | ~JQ | Terminate Zebra BASIC Interpreter |
| ~JR | ~JR | Power On Reset |
| ^JS | ^JSa | Sensor Select |
| ~JS | ~JSb | Change Backfeed Sequence |
| ^JT | ^JT####,a,b,c | Head Test Interval |
| ^JU | ^JUa | Configuration Update |
| ^JW | ^JWt | Set Ribbon Tension |
| ~JX | ~JX | Cancel Current Partially Input Format |
| ^JZ | ^JZa | Reprint After Error |
| ~KB | ~KB | Kill Battery (Battery Discharge Mode) |
| ^KD | ^KDa | Select Date and Time Format (for Real Time |
| ^KL | ^KLa | Define Language |
| ^KN | ^KNa,b | Define Printer Name |
| ^KP | ^KPa,b | Define Password |
| ^KV | ^KVa,b,c,d,e | Kiosk Values |
| ^LF | ^LF | Print Font Links |
| ^LH | ^LHx,y | Label Home |
| ^LL | ^LLy | Label Length |
| ^LR | ^LRa | Label Reverse Print |
| ^LS | ^LSa | Label Shift |
| ^LT | ^LTx | Label Top |
| ^MA | ^MAtype,print,threshold,frequency,units | Set Maintenance Alerts |
| ^MC | ^MCa | Map Clear |
| ^MD | ^MDa | Media Darkness |
| ^MF | ^MFp,h | Media Feed |
| ^MI | ^MItype,message | Set Maintenance Information Message |
| ^ML | ^MLa | Maximum Label Length |
| ^MM | ^MMa,b | Print Mode |
| ^MN | ^MNa,b | Media Tracking |
| ^MP | ^MPa | Mode Protection |
| ^MT | ^MTa | Media Type |
| ^MU | ^MUa,b,c | Set Units of Measurement |
| ^MW | ^MWa | Modify Head Cold Warning |
| ^NC | ^NCa | Select the Primary Network Device |
| ~NC | ~NC### | Network Connect |
| ^ND | ^NDa,b,c,d,e,f,g,h,i,j | Change Network Settings |
| ^NI | ^NI### | Network ID Number |
| ~NR | ~NR | Set All Network Printers Transparent |
| ^NS | ^NSa,b,c,d,e,f,g,h,i | Change Wired Networking Settings |
| ~NT | ~NT | Set Currently Connected Printer Transparent |
| ^PA | ^PAa,b,c,d | Advanced Text Properties |
| ^PF | ^PF# | Slew Given Number of Dot Rows |
| ^PH | ^PH or ~PH | Slew to Home Position (Alt. ~PH) |
| ~PL | ~PLa | Present Length Addition |
| ^PM | ^PMa | Printing Mirror Image of Label |
| ^PN | ^PNa | Present Now |
| ^PO | ^POa | Print Orientation |
| ^PP | ^PP or ~PP | Programmable Pause (Alt. ~PP) |
| ^PQ | ^PQq,p,r,o,e | Print Quantity |
| ~PR | ~PR | Applicator Reprint |
| ^PR | ^PRp,s,b | Print Rate |
| ~PS | ~PS | Print Start |
| ^PW | ^PWa | Print Width |
| ~RO | ~ROc | Reset Advanced Counters |
| ^SC | ^SCa,b,c,d,e,f | Set Serial Communications |
| ~SD | ~SD## | Set Darkness |
| ^SE | ^SEd:o.x | Select Encoding Table |
| ^SF | ^SFa,b | Serialization Field (with a Standard ^FD |
| ^SI | ^SIa,b | Set Sensor Intensity |
| ^SL | ^SLa,b | Set Mode and Language (for Real-Time Clock) |
| ^SN | ^SNv,n,z | Serialization Data |
| ^SO | ^SOa,b,c,d,e,f,g | Set Offset (for Real-Time Clock) |
| ^SP | ^SP# | Start Print |
| ^SQ | ^SQa,b,c | Halt ZebraNet Alert |
| ^SR | ^SR#### | Set Printhead Resistance |
| ^SS | ^SSw,m,r,l,m2,r2,a,b,c | Set Media Sensors |
| ^ST | ^STa,b,c,d,e,f,g | Set Date and Time (for Real-Time Clock) |
| ^SX | ^SXa,b,c,d,e,f | Set ZebraNet Alert |
| ^SZ | ^SZa | Set ZPL Mode |
| ~TA | ~TA### | Tear-off Adjust Position |
| ^TB | ^TBa,b,c | Text Blocks |
| ^TO | ^TOs:o.x,d:o.x | Transfer Object |
| ~WC | ~WC | Print Configuration Label |
| ^WD | ^WDd:o.x | Print Directory Label |
| ~WQ | ~WQquery-type | Write Query |
| ^XA | ^XA | Start Format |
| ^XB | ^XB | Suppress Backfeed |
| ^XF | ^XFd:o.x | Recall Format |
| ^XG | ^XGd:o.x,mx,my | Recall Graphic |
| ^XS | ^XSlength,threshold | Set Dynamic Media Calibration |
| ^XZ | ^XZ | End Format |
| ^ZZ | ^ZZt,b | Printer Sleep |


## ZPL RFID Commands

| Command | Format | Description |
| ------- | ------ | ----------- |
| ^HL | ^HL or ~HL | Return RFID Data Log to Host (Alt. ~HL) |
| ^HR | ^HRa,b,c,d,e | Calibrate RFID Tag Position |
| ^RA | ^RA#,f,r,m,b | Read AFI or DSFID Byte |
| ^RB | ^RBn,p0,p1,p2, ..., p15 | Define EPC Data Structure |
| ^RE | ^REt,r | Enable/Disable E.A.S. Bit |
| ^RF | ^RFo,f,b,n,m | Read or Write RFID Format |
| ^RI | ^RIa,b,c,d | Get RFID Tag ID |
| ^RL | ^RLM,k,a,e,u | Lock/Unlock RFID Tag Memory |
| ^RL | ^RLB,s,n | Lock/Unlock RFID Tag Memory |
| ^RM | ^RMe | Enable RFID Motion |
| ^RN | ^RNe | Detect Multiple RFID Tags in Encoding Field |
| ^RQ | ^RQf,c,o[data] | Quick Write EPC Data and Passwords |
| ^RR | ^RRn,a | Specify RFID Retries for a Block or Enable |
| ^RS | ^RSt,p,v,n,e,a,c,s | Set Up RFID Parameters |
| ^RT | ^RT#,b,n,f,r,m,s | Read RFID Tag |
| ^RU | ^RUa,b | Read Unique RFID Chip Serialization |
| ~RV | ~RVa | Report RFID Encoding Results |
| ^RW | ^RWr,w,a | Set RF Power Levels for Read and Write |
| ^RZ | ^RZp,m,l | Set RFID Tag Password and Lock Tag |
| ^WF | ^WFr,m,w,f,b | Encode AFI or DSFID Byte |
| ^WT | ^WTb,r,m,w,f,v | Write (Encode) Tag |
| ^WV | ^WVe | Verify RFID Encoding Operation |


## ZPL Wireless Commands

| Command | Format | Description |
| ------- | ------ | ----------- |
| ^KC | ^KCa,b,c,d | Set Client Identifier (Option 61) |
| ^NB | ^NBa | Search for Wired Print Server during |
| ^NN | ^NNa,b,c,d,e,f | Set SNMP |
| ^NP | ^NPa | Set Primary/Secondary Device |
| ^NT | ^NTa,b | Set SMTP |
| ^NW | ^NWa | Set Web Authentication Timeout Value |
| ^WA | ^WAa,b | Set Antenna Parameters |
| ^WE | ^WEa,b,c,d,e,f,g,h | Set WEP Mode |
| ^WI | ^WIa,b,c,d,e,f,g,h,i | Change Wireless Network Settings |
| ^WL | ^WLa,b,c | Set LEAP Parameters |
| ~WL | ~WL | Print Network Configuration Label |
| ^WP | ^WPa,b | Set Wireless Password |
| ^WR | ^WRa,b,c,d,e | Set Transmit Rate |
| ~WR | ~WR | Reset Wireless Radio Card and Print Server |
| ^WS | ^WSe,o,p,h,i,j,k | Set Wireless Radio Card Values |
| ^WX | ^WXa,... | Configure Wireless Securities |
| ^WX | ^WX01 | Configure Wireless Securities |
| ^WX | ^WX02,b,c,d,e,f,g,h | Configure Wireless Securities |
| ^WX | ^WX03,b,c,d,e,f,g,h | Configure Wireless Securities |
| ^WX | ^WX04,k | Configure Wireless Securities |
| ^WX | ^WX05,i,j | Configure Wireless Securities |
| ^WX | ^WX06,i,j,k | Configure Wireless Securities |
| ^WX | ^WX07,i,j | Configure Wireless Securities |
| ^WX | ^WX08,i,j | Configure Wireless Securities |
| ^WX | ^WX09,n | Configure Wireless Securities |
| ^WX | ^WX10,k | Configure Wireless Securities |
| ^WX | ^WX11,i,j | Configure Wireless Securities |
| ^WX | ^WX12,i,j,k | Configure Wireless Securities |
| ^WX | ^WX13,i,j | Configure Wireless Securities |
| ^WX | ^WX14,i,j | Configure Wireless Securities |
| ^WX | ^WX15,i,j,l,m | Configure Wireless Securities |


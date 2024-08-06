
  README


       The diskette contains the data set on educational attainment at various
  levels for the male and female population. The data set includes estimates
  of educational attainment for the population by age - over age 15 and over
  age 25 - for 126 countries in the world. (see Barro, Robert and J.W. Lee,
  "International Measures of Schooling Years and Schooling Quality, AER, Papers
  and Proceedings, 86(2), pp. 218-223 and also see
  "International Data on Education", manuscipt.) Data are presented
  quinquennially for the years 1960-1990.  

Please note that the data and description on the measures of schooling quality and educational inequality is in the file "quality.xls" (Excel 5.0)

       The diskette has six plain ASCII (text) files - school1.raw,
  school2.raw, school3.raw, school4.raw, school5.raw and school6.raw.  Each of
  the files contains data as described below.  Data on each variable are
  listed by the order of SHCODE (see List of Country).  The missing
  observations are denoted by '.'.  The term 'xx' behind a variable denotes an
  age group of the population (xx= 25 applies to the population aged 25 and
  over and xx= 15 appiles to the population aged 15 and over.)


  ASCII File                   Data
  -----------                  -----

  SCHOOL1.RAW    : SHCODE YEAR N025 PRI25 PRIC25 SEC25 SECC25 HIGH25 HIGHC25
                   TYR25 PYR25 SYR25 HYR25

  SCHOOL4.RAW    : SHCODE YEAR N015 PRI15 PRIC15 SEC15 SECC15 HIGH15 HIGHC15
                   TYR15 PYR15 SYR15 HYR15


  Variable  :       Definition
  ____________________________________________________________________________

  SHCODE    : Numerical code in Barro-Lee data set and Summers-Heston v.5.0.

  YEAR      : Year (60, 65, 70, 75, 80, 85 and 90)

  NO        : Percentage of "no schooling" in the total population

  NOM       : Percentage of "no schooling" in the male population

  NOF       : Percentage of "no schooling" in the female population

  PRI       : Percentage of "primary school attained" in the total pop.

  PRIM      : Percentage of "primary school attained" in the male pop.

  PRIF      : Percentage of "primary school attained" in the female pop.

  PRIC      : Percentage of "primary school complete" in the total pop.

  PRICM     : Percentage of "primary school complete" in the male pop.

  PRICF     : Percentage of "primary school complete" in the female pop.

  SEC       : Percentage of "secondary school attained" in the total pop.

  SECM      : Percentage of "secondary school attained" in the male pop.

  SECF      : Percentage of "secondary school attained" in female pop.

  SECC      : Percentage of "secondary school complete" in the total pop.

  SECCM     : Percentage of "secondary school complete" in the male pop.

  SECCF     : Percentage of "secondary school complete" in female pop.

  HIGH      : Percentage of "higher school attained" in the total pop.

  HIGHM     : Percentage of "higher school attained" in the male pop.

  HIGHF     : Percentage of "higher school attained" in female pop.

  HIGHC     : Percentage of "higher school complete" in the total pop.

  HIGHCM    : Percentage of "higher school complete" in the male pop.

  HIGHCF    : Percentage of "higher school complete" in female pop.

  TYR       : Average schooling years in the total population.

  TYRM      : Average schooling years in the male population.

  TYRF      : Average schooling years in the female population.

  PYR       : Average years of primary schooling in the total population.

  PYRM      : Average years of primary schooling in the male population.

  PYRF      : Average years of primary schooling in the female population.

  SYR       : Average years of secondary schooling in the total population.

  SYRM      : Average years of secondary schooling in the male population.

  SYRF      : Average years of secondary schooling in the female population.

  HYR       : Average years of higher schooling in the total population.

  HYRM      : Average years of higher schooling in the male population.

  HYRF      : Average years of higher schooling in the female population.
  ____________________________________________________________________________

  

                                  COUNTRY LIST
                                  -------------
    SHCODE     : Country code (as in Barro-Lee data set)

  ____________________________________________________________________________

      SHCODE      World Bank Code        COUNTRY  NAME

        1            DZA                  Algeria
        2            AGO                  Angola
        3            BEN                  Benin
        4            BWA                  Botswana
        5            HVO                  Burkina Faso
        6            BDI                  Burundi
        7            CMR                  Cameroon
        8            CPV                  Cape verde
        9            CAF                  Central African Rep.
       10            TCD                  Chad
       11            COM                  Comoros
       12            COG                  Congo
       13            EGY                  Egypt
       14            ETH                  Ethiopia
       15            GAB                  Gabon
       16            GMB                  Gambia
       17            GHA                  Ghana
       18            GIN                  Guinea
       19            GNB                  Guinea-Bissau
       20            CIV                  Cote d'Ivoire
       21            KEN                  Kenya
       22            LSO                  Lesotho
       23            LBR                  Liberia
       24            MDG                  Madagascar
       25            MWI                  Malawi
       26            MLI                  Mali
       27            MRT                  Mauritania
       28            MUS                  Mauritius
       29            MAR                  Morocco
       30            MOZ                  Mozambique
       31            NER                  Niger
       32            NGA                  Nigeria
       33            RWA                  Rwanda
       34            SEN                  Senegal
       35            SYC                  Seychelles
       36            SLE                  Sierra Leone
       37            SOM                  Somalia
       38            ZAF                  South africa
       39            SDN                  Sudan
       40            SWZ                  Swaziland
       41            TZA                  Tanzania
       42            TGO                  Togo
       43            TUN                  Tunisia
       44            UGA                  Uganda
       45            ZAR                  Zaire
       46            ZMB                  Zambia
       47            ZWE                  Zimbabwe
       48            BHS                  Bahamas, The
       49            BRB                  Barbados
       50            CAN                  Canada
       51            CRI                  Costa Rica
       52            DMA                  Dominica
       53            DOM                  Dominican Rep.
       54            SLV                  El Salvador
       55            GRD                  Grenada
       56            GTM                  Guatemala
       57            HTI                  Haiti
       58            HND                  Honduras
       59            JAM                  Jamaica
       60            MEX                  Mexico
       61            NIC                  Nicaragua
       62            PAN                  Panama
       63            LCA                  St.Lucia
       64            VCT                  St.Vincent & Grens.
       65            TTO                  Trinidad & Tobago
       66            USA                  United States
       67            ARG                  Argentina
       68            BOL                  Bolivia
       69            BRA                  Brazil
       70            CHL                  Chile
       71            COL                  Colombia
       72            ECU                  Ecuador
       73            GUY                  Guyana
       74            PRY                  Paraguay
       75            PER                  Peru
       76            SUR                  Suriname
       77            URY                  Uruguay
       78            VEN                  Venezuela
       79            AFG                  Afghanistan
       80            BHR                  Bahrain
       81            BGD                  Bangladesh
       82            BUR                  Myanmar (Burma)
       83            CHN                  China
       84            HKG                  Hong Kong
       85            IND                  India
       86            IDN                  Indonesia
       87            IRN                  Iran, I.R. of
       88            IRQ                  Iraq
       89            ISR                  Israel
       90            JPN                  Japan
       91            JOR                  Jordan
       92            KOR                  Korea
       93            KWT                  Kuwait
       94            MYS                  Malaysia
       95            NPL                  Nepal
       96            OMN                  Oman
       97            PAK                  Pakistan
       98            PHL                  Philippines
       99            SAU                  Saudi Arabia
      100            SGP                  Singapore
      101            LKA                  Sri Lanka
      102            SYR                  Syria
      103            OAN                  Taiwan
      104            THA                  Thailand
      105            ARE                  United Arab Emirates
      106            YEM                  Yemen, N.Arab
      107            AUT                  Austria
      108            BEL                  Belgium
      109            CYP                  Cyprus
      110            DNK                  Denmark
      111            FIN                  Finland
      112            FRA                  France
      113            DEU                  Germany, West
      114            GRC                  Greece
      115            HUN                  Hungary
      116            ISL                  Iceland
      117            IRL                  Ireland
      118            ITA                  Italy
      119            LUX                  Luxembourg
      120            MLT                  Malta
      121            NLD                  Netherlands
      122            NOR                  Norway
      123            POL                  Poland
      124            PRT                  Portugal
      125            ESP                  Spain
      126            SWE                  Sweden
      127            CHE                  Switzerland
      128            TUR                  Turkey
      129            GBR                  United Kingdom
      130            YUG                  Yugoslavia
      131            AUS                  Australia
      132            FJI                  Fiji
      133            NZL                  New Zealand
      134            PNG                  Papua New Guinea
      135            SLB                  Solomon Islands
      136            TON                  Tonga
      137            VUT                  Vanuatu
      138            WSM                  Western Samoa
      140            LBY                  Libya
      141            NAM                  Namibia
      142                                 Reunion
      143            BLZ                  Belize
      144            BRN                  Brunei
      145                                 Antigua & Barbados
      146            KNA                  St.Kitts& Nevis
      150            BGR                  Bulgaria
      151            CSK                  Czechoslovakia
      152            DDR                  Germany, East
      153            ROM                  Romania
      154                                 U.S.S.R.
      155                                 Cuba
      156            ALB                  Albania


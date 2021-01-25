### **Directions API (JSON Return)**

* Follow instructions for directions and form a URL to provide route directions in JSON
* Directions from Royal Tyrrell Museum to Hoodoos Trail 
* Get Directions: [HERE](https://maps.googleapis.com/maps/api/directions/json?origin=Royal+Tyrrell+Museum&destination=Hoodoos+Trail&key=AIzaSyBLd0Hl7PVa0PnyZVIlLrAUipqZ6npRSYA)
  * https://maps.googleapis.com/maps/api/directions/json?origin=Royal+Tyrrell+Museum&destination=Hoodoos+Trail&key=AIzaSyBLd0Hl7PVa0PnyZVIlLrAUipqZ6npRSYA
  
  ### JSON Return
  '''
  {
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJy38C1IcSc1MR1Bh0FOdJtRI",
         "types" : [ "establishment", "museum", "point_of_interest", "tourist_attraction" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJtYG4v7XLcFMRtEf31e5R-fI",
         "types" : [ "route" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 51.4785254,
               "lng" : -112.7006986
            },
            "southwest" : {
               "lat" : 51.038619,
               "lng" : -115.547679
            }
         },
         "copyrights" : "Map data ©2021 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "258 km",
                  "value" : 258036
               },
               "duration" : {
                  "text" : "2 hours 46 mins",
                  "value" : 9935
               },
               "end_address" : "Hoodoos Trail, Improvement District No. 9, AB, Canada",
               "end_location" : {
                  "lat" : 51.1847462,
                  "lng" : -115.547679
               },
               "start_address" : "1500 N Dinosaur Trail, Drumheller, AB T0J 0Y0, Canada",
               "start_location" : {
                  "lat" : 51.4785254,
                  "lng" : -112.7868215
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 573
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 53
                     },
                     "end_location" : {
                        "lat" : 51.47403449999999,
                        "lng" : -112.7830225
                     },
                     "html_instructions" : "Head \u003cb\u003esoutheast\u003c/b\u003e toward \u003cb\u003eN Dinosaur Trail\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAB-838 E\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ykeyHrtkoTNWVa@DE\\]@A^SBA\\OBAzAk@^SFGVUlAqAPSx@cAz@cAZa@\\_@Za@\\a@^e@\\]\\YDEl@[`@IvAS"
                     },
                     "start_location" : {
                        "lat" : 51.4785254,
                        "lng" : -112.7868215
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "5.2 km",
                        "value" : 5187
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 292
                     },
                     "end_location" : {
                        "lat" : 51.4714541,
                        "lng" : -112.7129123
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eN Dinosaur Trail\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAB-838 E\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "uodyHz|joTWaGIsBGaBAi@?Q?q@BaABuAFiAFo@Fo@Fg@N}@Hg@F]BMRy@Ps@F]|@uDDSFWH[Pq@DS\\oADQJ_@VaAZoA\\{ABMFSNm@Ni@Lc@@CL[Ti@HSTe@NYJQHKRUBGVW?ARSn@o@|@}@VU\\]\\]^]\\]pA}ARYV_@NYDIZk@\\y@FOVm@Tu@VkAT}@N{@FWD]Fi@PuAHiA@SDs@F}@LwBLcC@_@F{@FuAJqBHeBJ}BH{ADaAH_CJiC?gH@sK?y@?w@@sB?y@?eB?MCy@GqBAy@OqFGi@k@aFaAaEgBuH_@gESgCk@}Gu@sJ]gDY{BK}@UgBa@_DQ}AG}@CYC]Iw@MwBIgBEw@EkB?IAs@AyBCkDFi@AkD?y@EyIAs@?EA]Ce@C}@k@sHSiCcBwUIkAC]GcBCiBEuB?M?eA@a@@mC@_@@mA@y@?u@FeD?I?gAGqG?yC?y@?mDFoG?_E"
                     },
                     "start_location" : {
                        "lat" : 51.47403449999999,
                        "lng" : -112.7830225
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.1 km",
                        "value" : 1137
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 136
                     },
                     "end_location" : {
                        "lat" : 51.4619655,
                        "lng" : -112.7107917
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eAB-56 S\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAB-9 W\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "q_dyHtf}nTJ_@BI@C@CDGDCBCBAZO~Ct@fBb@fCj@TDJ@@@N@H@HAHADABA@ABC?ABEHCFCBCDEHGHIHMHKDKfAoBr@oAXg@Xg@`@u@JSFGDGROFEDCHEFCNEHANCN?zAAfA?V?`@@b@?pD?|A?`B?j@Af@?FH|ABJ@b@@j@@"
                     },
                     "start_location" : {
                        "lat" : 51.4714541,
                        "lng" : -112.7129123
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 822
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 82
                     },
                     "end_location" : {
                        "lat" : 51.4579442,
                        "lng" : -112.7011356
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eS Railway Ave\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAB-56 S\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAB-9 W\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "idbyHly|nTT@BYV_CBUD]RcBr@aFPcAH_@F[DS@CFWFS@AFSFSJYLYVi@r@_B`BqDzC{GzAgD`@aAb@eARk@DMDQFQDQ^}A"
                     },
                     "start_location" : {
                        "lat" : 51.4619655,
                        "lng" : -112.7107917
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "62.6 km",
                        "value" : 62559
                     },
                     "duration" : {
                        "text" : "38 mins",
                        "value" : 2293
                     },
                     "end_location" : {
                        "lat" : 51.3869821,
                        "lng" : -113.5211162
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eAB-9 W\u003c/b\u003e (signs for \u003cb\u003eCalgary\u003c/b\u003e)",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ckayHb}znTHCB?BCHMDGFEDEDEJId@[n@AzE@@?rD@nDA|C@bEAZ?N?N?lADbBFZ@Z@h@?x@?tAAfAAfA?b@AfA?b@Ab@?BADA@AFIvA?R?f@?v@Ah@?R@P@F?H@J@J@@@LBLBFBB@HDTLLJLL@?NNJNFFRZ@?Xb@FFRZv@hAv@fANTb@l@r@`A`@h@v@fADFlA`B\\b@DHjB`CZb@Zb@FHlA~An@|@FF\\b@Z`@Z`@\\`@v@dA\\`@Zb@tAfBNPLLTVFDPLNFFDXJf@H^?@?n@CTCb@C@?`@Ct@Ed@?NBL@RDD@\\Jf@PXFXDR@TAFATC\\If@UJG^UXOz@i@f@MHAPCd@?`@Bl@HlAV`@HJ@VFb@HdATvAXzBf@jCj@fBb@b@HNDbA^t@\\|@f@b@\\VPrAnAdAdAb@`@|AzAx@v@lAlAfDhDxBtBjIfIZXzAxA\\\\vDrDhBhBdAhAx@z@pA~Ab@n@dBpC^n@FJPZZl@r@zAf@fAl@zAPd@t@rB`@pAXbAT|@Tp@|@bDtAvEv@fC|ArFd@~Ab@dBNr@TdA\\jB`@jC@HFj@Jv@Ht@PjBLfBLbCJxCBtB@~A?jD?jQ?x@@l_@?x@?xR?rT?x@?x@?dF?jD?x@@fF?x@?v@?x@?x@?rB?x@?v@?x@?xI?rB?x@?x@?v@?x@?bA?n@?x@?x@?x@?v@?x@?x@?x@?x@?pB?x@?rK?x@?xM@hG?nF?dD@dF?F?|E?tD?jB?v@?`A?vG?rB?dF?nF?bD?x@?`A?vG@~G?x@?zB?fE?dF?^?rJ?lD?vA?X?x@?lD?pC@nY?rT?rB?v@?lD?rB?rK?dF?r]?z[@xC?bF?n[?lM?fF?~G?pB?rB?x@?rB?v@?rK?lM?x@?rK?fX?jNApg@?`G?rB?jD?rBAlV?dF?D?`X?fF?dF?dF?lDAx@?hU?tC?x@?~G?vA?xB@lA?R@d@@j@BjAH~AHrAXvCLjAPlAXbBF\\Nr@Nr@@BR~@h@jB`@nAh@vAZr@n@vAvAdCrAbC~AhCp@hAPZdE~G`AxAz@hAv@v@DF\\\\NNNJ^XHFf@^LHd@X|@d@@?`@PPHdA\\dAV~@Nf@F@?b@DH@hABV@fC@F?b@?hB@b@?b@@b@?lA?dB@b@?vE?R?r@?b@?rD?D?\\?jBBB?bAFJ?z@FN@R@dALbBVF@rAVTDb@Jt@Rp@Tz@VpClAtBfAtBnAzAdAf@ZjA~@DDXVj@f@|@z@t@r@~@bARVvAbBJNtAnBrAnBrA~BfAtBzA~Ch@nArAjDrAxD@BPj@d@~APh@x@`Dd@rBh@fCbArFPfA@JHh@NbAFh@VjBBR^lDBZFv@R~BR~CNzCDjABl@@j@BdAD`B?PD|C?L?x@@lD?xR?pK?x@?x@?jD?lM?dF?x@AdF?zB?jB?xR?x@?pT?x@?fF?pB?~J?|G?bB?hJ?pB?fF?jD?rB?pB?x@?lD?dO?x@?dF?x@?rK?rT?dN?pD?zHAzMAlM?x@?x@ApK?~GA`HAlH?vA?pF@d@?`B?~@@jI?~B@j@?L?rK?nC?hE@R?vC?r@?DArB?x@?d@?jA?pB?z@@x@?~G?ZAbG?r@?|@?x@?x@?rB?F?hB@lD?pB?|@?vG?BAxCAfL?dFAjDAlD?x@DhL?zA?^CvBARAx@Ap@IxBEtACZE~@MhB?FGn@En@AFQnBAFOrAQrAGh@Mv@ALc@hCOz@Or@AHMh@Op@GX[jA?@Ql@Qp@ENi@lB[hAYhAq@rCIZMn@WlAI\\AFUlA]jBCNKt@ERQnAYxBM~@Iz@U`CKnAKtAItAIpACl@ErAGpAAf@A`@?FAf@?HA|@?HGhHAd@?x@CvBEfDAx@C|BGfJAtBAZ?x@AfAE|CAx@Ax@ClDGfFEhD?x@EhDGzI?HAzA@vA@f@D|BBn@B|@FhBHrB@FJhB@PBf@H`ADl@Fv@?FPfBBTPtAJr@XlBHd@PdA@HJh@F`@VjA^zAb@hBhApE^xAb@~Av@tCt@xCf@rBd@tBRx@@JNp@TnATnA@@RrADRVfB?BJt@LdAP~AD`@JlAJnAB^Fv@BTB`@B`@@TF~@DlAFtA@d@@RD`BB`B@`@DjD@n@?H?x@@pB@x@?x@@x@?d@?R?v@@~BAl@ArBAv@ArBAnA?b@Av@Ax@EjDAv@?@CrB?LAj@CpBC`AAp@CpBAx@?DGfFAp@ApB?x@AH?hBAx@?~@AdD?x@?p@A~E?pD@lK@vS?lK?lD?x@AxI?jD?x@?|@@xH@Z@vFApG?nB?v@?hB?vD?pB?~G?rB?N?zC?xI?x@?x@Ax@?`B@bC?lD?jD?~G?x@?jD?lD?|B?fT?|E?tD?lD?pK?lD?pB?`H?lF@p@?x@?dD?jF?vC?T?xI?vC?nI?fF?T?x@?hF?hD?dG?X?x@?hF?t@ArB?|D?zL?pB?x@?pC?tS?pB?x@?F?hEAtHAbD?tB?pC?fD?zJ?nD?lF?dD?pT?x@ArB?dF?r@?xB?jDArB?fE?\\?x@?rB?v@?L?dB?P?f@?hE?nC?pB?pB?@AvFAtE?lD?jC?nEA|F?vA?rA?~G?zF?jG?rK?v@?x@?bE@zS?x@?fF?pK?zI?pB?zB?n@?x@?x@?lL@xF?dB?L?x@?v@?`H?f@?hA?rB?pB?x@?lD?pB?t@?B?x@?rB?~G?pB?rB?j@?L@rK?D?jK?x@@lV?jM?rB?dF@|H@dFBdR?fC?jDAtD?`Q@`D?x@?lD?pB?x@@jB?rD?x@?vF?xJ?`A?x@AdF?VAfGE~G?fD?rK?~F@zJAbL?rB?pA?`@?v@ArB?rB?v@ArB?rB?x@?`AAhB?zH?vAArE@dC?x@?bE?zA?v@@tJ?\\BlM?dOArB?dF?x@?jD?x@?~G?x@AvF?f@?X?rC@dF?tC?T?x@?tG?bA?x@?rBAnF?hB?rC?V?dF?hB?tD?x@?jCA|H@tD?dJ?v@?x@?rB@jD?rB?dO?`H?dF?pB?fF?dF?rB?v@?fO?jD?xQ?x@?lD?x@?v@?rK?~G?xI?lV?x@?jV?x@?xI?x@?jD?fF?dF?t^@pJ?zG?jM?dF?x@?rT?x@?dO?lD?x@?pK?tIA~P?x@?vW@~P?lD?pK?rK?x@?~P@xR?x[?x@?lM?x@@jJApJ?lD?v@?l_@?x@?~G?x@?rT?x@AjM?rB?rT?x@?v@?x@?rB?x@?~G?~G?dX@rB?x@?~G?x@?x@?xI?v@?x@?rB?hQ?n@?jDAxI?rBA`HBbF@~H?jI?zI?dF?~G?x@A~P?`H?dF?xIAdF?x@?dX?x@?lDAxR?dF?x@?bA?bU?rBAdX?rB?rB?~P?x@?dF?nE?fMAhM?dE?pEA`L?jM?x@?lM?vH?pR@z@?lJ?nC?|Q?lM?xI?dO?~G@h`@?r]?zA@fp@?nDAvABdH?D?bG@zC"
                     },
                     "start_location" : {
                        "lat" : 51.4579442,
                        "lng" : -112.7011356
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "24.8 km",
                        "value" : 24845
                     },
                     "duration" : {
                        "text" : "15 mins",
                        "value" : 898
                     },
                     "end_location" : {
                        "lat" : 51.212436,
                        "lng" : -113.678823
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eAB-9 W\u003c/b\u003e (signs for \u003cb\u003eIrricana\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eCalgary\u003c/b\u003e)",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "sosxH~a{sTd@?H@lAT^JB@ZL^JXPHFt@n@`BfBNPdIxIfI|InAtAb@d@h@h@p@t@hG~Gn@r@tEbFrAxAxA~AbAhAbHxHrKnL\\^rD~DVXvEdF\\^\\^jCtCd@h@\\^tC`D^`@`@`@nAvAf@j@p@v@j@r@f@t@FH\\j@l@bA\\n@HPt@xA`ApBdAvBh@fA`AnBdAvBtBnEpAjCxBtEXl@xI|QVh@DFzA`DhBrDzFtL^z@\\p@dAxBv@~At@zAn@tAJRLVz@hBdCdFhKnTlEbJn@nAVh@rArClAbChA`Cb@|@`@v@`@z@`@z@f@bAnAjCj@jAdAzBTd@Vf@vChGt@|A~CrGt@~AhA~B^r@Xl@HNh@jAf@`AjBzDr@xA~GxNn@tAnC`GjBnD|EhInCtD`CrCnBtBd@b@b@`@nC~BtCrBnAx@f@XTL`@Rh@Xp@XvAh@z@^v@ZhA\\n@P`Bd@fB^p@J`@F~@NdCRvBJfDBr@@zB?|D@|A?pHChG?`KFrDBpCBvECtE@x@@bF@h@?jC?nC@b@?nC@b@?jB?nEA|E?~PCb@?fSAj]EnDAb@?~GCtC@|D@nCAb@?nDAjA?zSBjGBR?rKD`B?lTB`P@Z?b@?l^?h@@j@D|@Lv@N^HZH|Ah@nBbAx@h@v@l@f@`@dAdAp@x@r@~@NTZd@NV\\l@`@r@P^d@bA^~@\\`AZ`ARl@Pn@VdAPp@@HJ`@RlANv@XnBJ`AJ`AD^Dh@Fx@HdBFdBBr@@x@@bD?fB?hA?nA?xC?t@?p]?BAvE@xDAfJ@dG?`G?p@@|C?pB?j@?lFPxG^bG\\bDl@rDb@xCr@fD@HfAbEfAzCv@|Bv@jBjBnCpBxCbAjA\\^RVtB|BjClBPJNHnD|A~@XhBf@\\LpLfAnIC~GCb@?bICjBAP?rRCb@?~@?j@?jBAb@A|ICjJFD@fAH|@HH@hB\\`@F?@|CbAd@PJHVPFD~@x@~AvAhAhA|@hAv@pAr@vArBpEBHx@fCRx@b@jB`@rB|A|Ix@nExFz[?@dBlJx@rEZfBTjAb@fCLr@v@rEX`BvCtPDTR`A@HNx@`@bC`AbFp@fDPr@V`AXx@\\bAd@pAv@dBh@dAp@fAt@jATVh@p@p@t@vArA@@j@`@hAv@lCxAnFtCrFnCxAv@fDfBt@^tEbCdCrAhAl@z@`@dBx@`Af@hCtApC`B|@l@^VNHnCzBjA`ApCdCdDxCp@j@tBhBbBzAtApAnD`DnAhAr@n@fB|AxEhEfA~@v@l@dAt@z@j@B@`Ah@z@`@dA`@dA`@"
                     },
                     "start_location" : {
                        "lat" : 51.3869821,
                        "lng" : -113.5211162
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "22.6 km",
                        "value" : 22636
                     },
                     "duration" : {
                        "text" : "16 mins",
                        "value" : 965
                     },
                     "end_location" : {
                        "lat" : 51.2125631,
                        "lng" : -114.0037483
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eAB-566 W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eTWP 262 W\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wlqwHr{ytTE~B?vI?bX?pKA|Y?pK?t[?x@?tYA`K?pT?|G?jDA~P?xC?jD?v@@pT?x@@tc@?hF?dFApK?jDA`a@?jD?rE@fM?dF?n]@vR?hA?jP?v[?zY?~G?pKAbX?~G?|GAjF?~RAn]?hMAjM?vI?lD?jDAt[?dF?|G?FC`c@?hVA|YA|G?jD?pGBbO@dF?jD@xE?|Y?dF?vF?pK?vI?|P?vR?jD?jD?dF?jM?nH@bO?~G?pB?hG@nA?v@?xI@v@?jA@pN@hP?xA?jC@bL@|P?dF@dF?xB?vD?|G?zB?n@AfOAfM?@?v@Cnf@?x@?bF?lDAvI?pB?fB?~SAbFAvC?bL?xC?dFAx@?pB?|PAdOAvI?fA?tE?~E?pDApT?`G?`G?`D?hC?x@?vF?~J?pI?bH?lLAdG?zC?p@?|MA|S?v@?L?vE?lC@fEAhJ?pI?~G?rM?`G?dA?H@nF?d@?rO?tE?vJ?jC@lE?pA?nO?xE?rA?vE?hB@tFAlDAbBArE?fC?lE?hI?P?`K?pB@pI?zH?rC?|B@hH?b@?|PEnA@~B?nB?v@@rB?nABnE?zA@lF?d@AhC?XAtE?tA@`C?|C?pC@jC?f@@nC?l@DbE@fBHzE?Z?rE?dFCdDEnD?`@I|FIdCE~BAxA?b@A~B@fA?XB`@?F@DBPAv@?R@~C?|A?f@?P?l@?bA?|@@bC?n@@zA"
                     },
                     "start_location" : {
                        "lat" : 51.212436,
                        "lng" : -113.678823
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "3.1 km",
                        "value" : 3108
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 123
                     },
                     "end_location" : {
                        "lat" : 51.184805,
                        "lng" : -114.0017199
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to merge onto \u003cb\u003eAB-2 S\u003c/b\u003e toward \u003cb\u003eCalgary\u003c/b\u003e",
                     "maneuver" : "ramp-left",
                     "polyline" : {
                        "points" : "omqwHljyvTj@ENGx@a@ZO^Sv@_@JGnBaAx@]XMhB{@^O^MZK\\IXGVENCXCVCbBEj@AlAApDEd@?\\Of@?nIAlG?`@?bLB~FAjKEp@?z@?^?b@?xF@fA?lC@l@?X?lC?b@?H?`B?dHAb@AjE?dH@b@?|QBjAA"
                     },
                     "start_location" : {
                        "lat" : 51.2125631,
                        "lng" : -114.0037483
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 325
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 12
                     },
                     "end_location" : {
                        "lat" : 51.18190440000001,
                        "lng" : -114.0020957
                     },
                     "html_instructions" : "Take exit \u003cb\u003e271\u003c/b\u003e for \u003cb\u003eAB-201\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eStoney Trail\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "_`lwHv}xvTHJFFL@hCLJ@Z@v@DlBHPBxDN"
                     },
                     "start_location" : {
                        "lat" : 51.184805,
                        "lng" : -114.0017199
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "10.0 km",
                        "value" : 10012
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 360
                     },
                     "end_location" : {
                        "lat" : 51.1536291,
                        "lng" : -114.1255144
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e at the fork, follow signs for \u003cb\u003eAlberta 201 W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eStoney Tr\u003c/b\u003e and merge onto \u003cb\u003eStoney Trail NW\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAB-201 W\u003c/b\u003e",
                     "maneuver" : "fork-right",
                     "polyline" : {
                        "points" : "{mkwHb`yvTHH@BB@F@dALl@F\\D`@H\\HXHZNVL\\Pd@\\XXVTFH@@JJX\\PV^l@LVDJN\\DJ@BN^Z|@^hAVv@j@`BRl@@BrArD@DVn@b@tABDL^Pn@Vx@Lj@@D@DDPT~@Pz@?D@DRfAV`BPtAPhBHdAFjABr@DjA?NFrB@n@BlB@z@?FBbB?bABXH\\CvW?|E@|EJ`Q@bC@tA@J@x@?@DrDHdGDnDFfGFhI@`D@fD@`D@fF?~H?bH?tHB`FBvBDnB?JB~@B~AJnCJnCHnBJdBDn@Dl@Dn@Bh@Df@Df@Fz@Fr@PhBN|A\\dD^rD^jDp@nGVhCRlB`@tDXtC@LDh@LnALdBLfBLvBLzCDjADzADnBBlA@n@@b@?jA@b@?n@?X?h@?f@?T?~@ClDIpCAr@IxCAf@IjCSxGYdJQvF_@bLw@zVEvBIvCIdCInCCv@QfFI~C[zKCr@EvAAd@C|BApB?tC@hBDzCFvBD~ADv@D`AH~A@NF|@L|ADp@TvBB^JdAFh@J|@?@TlBVdBRnATnA\\jBZ~A^~Af@vBFRJb@Pl@h@jB`@tA\\`An@fBb@hATn@r@bBf@fAp@vAR^Rb@`@p@`AbB\\j@t@lAt@bAr@~@hAvA\\`@z@~@bAdAb@`@JHdBzAr@j@PJ\\VdAp@x@j@d@VpAv@r@b@jBhA|@h@`@V|BtAx@j@JH^VpA`Al@d@JHr@j@JJh@d@PNXVn@n@f@d@h@n@zA`BhAnAz@dAj@v@lAbBz@nAfAbBLRJPv@pAr@pATb@x@xA`ArBDFPb@Vh@\\v@`A|BPf@^~@h@zAl@|A@BZ`A~@vCh@jBn@dC`@tAb@dBh@~Br@dDLn@Lv@@Bh@zCZjBBRN~@N~@BT"
                     },
                     "start_location" : {
                        "lat" : 51.18190440000001,
                        "lng" : -114.0020957
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "12.5 km",
                        "value" : 12473
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 482
                     },
                     "end_location" : {
                        "lat" : 51.0942073,
                        "lng" : -114.2335094
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to continue on \u003cb\u003eAB-201 W\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "e}ewHlcqwTR|ANfALhAD^BNLfANxAHz@HhAT~BRzCBf@Fz@JhBVhGNbG@X?^DvB@nA@fCArD?t@?nAGzJCpFAbBAx@CtDApDCpDM|TCjE@rH@nD?\\?j@BvIDbKLbM?v@@t@@nA@j@TbNDdBBv@\\`ODjB?DR|GFpBFnBb@`OBx@HhDNbFRxGLrFVbM^z\\XrW@nCH`GFlCB~@Bh@Bl@@n@Dt@Dt@D|@BVB^F`AH~@HbAJfAHv@J|@BVJv@LdAJt@Hb@BTLr@Lt@Nz@BNHb@Nt@Lp@Pv@Rx@?BPr@T~@Tv@XfANd@pBdGd@jAL\\j@rAXl@Zn@Rb@Xj@z@|Az@xAd@r@d@t@l@x@v@fAn@x@BDl@r@t@v@nBlBbCxBrAhA|AvA|AxAFFTTxAzAZ^\\d@\\b@^h@^j@T\\Tb@Xb@Tb@lA~Bt@bB`@dAbAlC?@l@hB~@nDdAdEPp@Tz@XhA`@jBf@lBdAnEz@nD\\tAhAjFb@bBNf@v@zC?@Pn@b@xAr@~B^dAr@tB|@xBf@lATh@Zr@t@|Al@jAj@fAl@fAz@tAz@rA\\f@T\\b@n@f@n@n@z@v@~@X\\JJPRTXVZJJ\\^dAdAfAdAt@l@hAz@p@d@n@`@@Bj@^DB`Aj@B@v@`@BBZPNHVLD@ZNZNFBnAh@LFf@PLDNDj@Rz@V@?|@TrAXZF@?dARtATXBvALdAHv@BhBDP?b@A`BAjCKLA`@Cb@EB?n@Iv@IfAQXEj@KhB_@t@S@?b@QjA[fAc@z@[lAg@vC{AlBgARMtCoBVS~BiBfA_AlAgAjCkCBCnEiEXUdAy@jAw@x@c@l@Wd@UdA]j@O`AU|ASl@G`AC`@Al@@l@BzALnANx@Pd@NVFdA`@`Ad@h@Xx@f@r@f@z@r@HHf@j@r@p@r@r@~CrDTVv@`ApArA\\XTTh@l@tAdAb@^\\X`@Xb@d@bAdAPP?@LLXZd@f@LLt@r@BBZXx@p@v@l@JHDBh@^nAt@BBrAp@l@Xj@T\\L|@\\|@V~@Tn@NTDh@Hj@Jf@Dn@HD?h@Dl@Bl@BV?"
                     },
                     "start_location" : {
                        "lat" : 51.1536291,
                        "lng" : -114.1255144
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 605
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 46
                     },
                     "end_location" : {
                        "lat" : 51.089585,
                        "lng" : -114.2376012
                     },
                     "html_instructions" : "Take the exit toward \u003cb\u003eValley Ridge Blvd NW\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "yizvHlffxTNNLFVFZFj@Fb@DVJVNDD^Xj@^t@f@r@f@rBxAXR|@h@f@\\f@Zn@f@DDZ^l@v@b@v@\\x@Xx@VjA"
                     },
                     "start_location" : {
                        "lat" : 51.0942073,
                        "lng" : -114.2335094
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 743
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 72
                     },
                     "end_location" : {
                        "lat" : 51.08976269999999,
                        "lng" : -114.2478842
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e at the fork to continue toward \u003cb\u003eValley Ridge Blvd NW\u003c/b\u003e",
                     "maneuver" : "fork-right",
                     "polyline" : {
                        "points" : "{lyvH~_gxTCt@Bz@Dz@H`BJjF?tC?PBnBFz@BjAJdBDt@PrEJbC@XDjA@bAGv@En@SvAq@vCUnA_@d@"
                     },
                     "start_location" : {
                        "lat" : 51.089585,
                        "lng" : -114.2376012
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 132
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 19
                     },
                     "end_location" : {
                        "lat" : 51.0894365,
                        "lng" : -114.2486071
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e3rd\u003c/b\u003e exit onto \u003cb\u003eValley Ridge Blvd NW\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "_nyvHf`ixTE?E?C@E@C@CBCBCDCBCDAFAD?@ADAF?D?F?F?F?D@F@D@D@D@DBDBDBBBBBBD@B@D@B?DABADABCBCBCBEBE^P"
                     },
                     "start_location" : {
                        "lat" : 51.08976269999999,
                        "lng" : -114.2478842
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 332
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 28
                     },
                     "end_location" : {
                        "lat" : 51.0886427,
                        "lng" : -114.2530172
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto the \u003cb\u003eTrans Canada Highway\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAB-1 W\u003c/b\u003e ramp to \u003cb\u003e16 Ave N\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eBanff\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "_lyvHxdixTXpAHFBBB@BBDDBB@BBB@B@DBDBF@B@D@FBFBH@F@J@F@J@LBR@V@RDr@HxAB`@@\\Dl@@f@@H@Z@T@p@@bA@dAHl@"
                     },
                     "start_location" : {
                        "lat" : 51.0894365,
                        "lng" : -114.2486071
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "28.0 km",
                        "value" : 28016
                     },
                     "duration" : {
                        "text" : "16 mins",
                        "value" : 959
                     },
                     "end_location" : {
                        "lat" : 51.1115467,
                        "lng" : -114.6434838
                     },
                     "html_instructions" : "Merge onto \u003cb\u003e16 Ave NW\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAB-1 W\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Trans-Canada Hwy/\u003cwbr/\u003eAB-1 W\u003c/div\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "_gyvHj`jxT?lG?fE?L?V?h@AzK?bF?rD?j@?~B?j@?L?vE?~B?j@?vD?r@?D?j@AvM?vE?dA?nP?hM?L?nGA~B?|C?L?x@?tE?N?h@?L?`X?dF?bB?fA?tE?LArB?v@?f@?vI?P?x@?xC?|D?d@?|D?f@?bC?jG?P?x@?hP?R?~A?PAjD?lB?tI?~SCxA@`M?fH?jD?jI?pR?X?^?X?pAApp@?V?pJ?vV?fA?nG?bK?bJ?x@?L?|C?|F?^?hE?pJ?dF?rF?`F?~@?|W?x@AnK?lB?x@?zA?N@\\?D?|ACl[?dJBhM?D?`VApG?fN?`G?zFAnD?`H@bI?~E?rV?pL?xC?|H?tN?v@?dG?tD?L?jD?xBAzF@lC?x@?b@?~D?|@?`K?fH?`T?pO?jB?bI?hJAxU@l@?pL?tG?P?zH?fJ?|K?|@?V?vA?hA?xS?zC@nI?xI?lF?vP?dX@vD@bCBnCDrBHnCJnCXhFPhCZvDv@pINbBHx@PjBPdBRvBb@|E\\lDTzCTtCH`BRrELnEFjF@pDAnDAtCG~NArCCjGMlYAtD?p@GhNAr@I|QArQGzJExIGvP?\\A\\C|IMz`@GzNA~BAv@IrQGxSCvKAjBEhMElLEhMCrFIfV?x@?t@CnDCjDAbFApFAv@CtIGrJEvLCnKGrGAr@Bh@?VAfBAx@CfH?dAEtAIfBI|AS~BG|@If@?@e@tDa@~Ba@rBo@`CY~@Od@Wv@g@|A}A|E}@nCSZa@vAMZsAfEM^sAzDg@`BWr@e@rASn@y@nCQf@YfAMj@On@]jBERYjBStA?@AFOfBGr@?BI~AIxBExB?xB@|A?H?HDxADlAJbBH|@@JD^PhBXjCLhAN|AFb@BPRpBNvABTb@dEXrC^`DRpBTtBFl@LfAfArKXnC\\|ELtBT`FFrBDzCBvB@tDAfGEhCKrDKpCGtBSfDe@vGQjBSlB_@rCs@bFk@xCq@fDoBzJe@zBkAzFqAfG_CzKOp@iE|S_@fBmA~F}C~NaArEo@xCkAvF{@jEo@dD{BhLI^ENUhAo@rC}@lEKf@iAnFcA~EMn@y@|DY~AyBjK}BzKiFhWaCfLiElSaBbIyC~NmBjJa@dB{@dEgJjd@Ot@On@m@xCQr@mChM}@nE_BrHgAxE"
                     },
                     "start_location" : {
                        "lat" : 51.0886427,
                        "lng" : -114.2530172
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "77.8 km",
                        "value" : 77754
                     },
                     "duration" : {
                        "text" : "44 mins",
                        "value" : 2636
                     },
                     "end_location" : {
                        "lat" : 51.2090213,
                        "lng" : -115.5312081
                     },
                     "html_instructions" : "Continue straight to stay on \u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAB-1 W\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "ev}vHvhvzTQnAUlAEVIf@I^qAtG]|Am@pCENe@lBKd@Od@i@dBAFgCpIeExNyEfP_BhFaBnFyDpMY~@mA~DSp@e@~Ay@pCuEnOSp@e@~Ae@~ASn@qBbHSp@mA|D_BnFUp@gCrIQl@eCrIcKj]cHlUSn@mDpLcAhDsB`H{@vCuA~EuAvEsCvJ_@lAADWx@wCbKw@`CaBtFMd@OX{@xCmEvNELIXi@fBQl@Qj@Ql@Oj@Ob@y@lCOj@]dAGPa@tAQj@o@vBCLQj@Sl@Ol@Qj@KZENQj@c@vASp@gCpIKZIZiA~D}@xCw@nCeArDi@jBqAlEiAvDiAzD_@rAu@fCu@fC{@lCgBdGqBdHmDtLQn@sDfM}C~JsB|GaBnFUv@a@tAe@~AoAdEe@zAUp@Wv@EJKXUl@[~@w@jBs@dBeA|Be@x@a@t@u@xAmAtBo@fAaCfEw@tAaBvCEDWf@Yf@gB|CgB|CkAvBYf@Yf@s@lAaCfEYd@Yf@mAvBkAvBYd@s@nAA@q@lAs@nAYd@?@mAtBkAvBYf@A@Wb@A@Yh@_CbEkAtBuDxGCBUb@u@rAy@zAaAnBKR_@`Ag@vAWv@Sn@Sl@]nA]tAYrAOp@i@fDOjAWzBUfCEn@El@KdBGzAC`BAnD?~A?R?P@`@@d@DfB@lADz@V`JTtIBp@@n@L|EBn@LvE^fNHnCBrAFdB?JNxDBh@Bv@?@JbBLtBVfCHz@XlCVhCL~@Fh@@JTlBD\\|@lGh@lDRxAPpAThBd@jDt@`GXxBr@zEj@zDr@tD`@jBp@pCf@nBz@lDz@fD~@vD`A`Er@nCnArFrAjFVfAj@`Cr@tCr@vCp@tCnExQPp@vEvR~AtGbBnHl@fDd@rCPnAn@vEPxAXnC^lELrBRrDDj@Bx@Dt@?@t@jRHnBVbINjDNhDl@`PPnEv@xSDjAFhARfGT`G^dJj@tMJ|Cb@dLR`FLpCPfET~FL`D\\pIX`JBh@z@vSNxDXzGXhHN`ELvCJbDLlCRbCN~A\\~BXtB^|Bt@fFp@tEn@lEn@nE|@lGnAfJp@vEJt@Jv@lApIn@lELt@@H`@tCLt@j@`E`@jCt@lFT~Ab@zCv@|FXrB|@dHl@vF^jD`@`Ef@`FzFfl@dCdWFt@r@dHfAfLn@tG|AlOTfCzAlOxBnTxCrZ`BbQl@vFd@|EtBvT`@lEdIzx@d@|EpCzXfA~KbDh\\xAbOz@xI?@JbAVxBTxATxATvAJ`@fAlE^pAPn@~DfNhE|NrI|YbBfG`EjN|ChKh@bBh@dBvCbK~CrKnDxLvAdFdAlDtGzThA`EjC|Ir@dCnFxQh@lBrAnEPn@fDjLh@hBxDpM~O|i@lAbEhCzIrBlHv@fCHVjMhc@X`AjC`JbB|FhBdGxA`F~BdIPn@t@bCtA|EpD~LpB`HRn@nB|G`CbIBH~@bDrB`HzBvHHXrHfWPl@Pp@Pl@zBzHhCrIv@jCPh@Tn@Vt@h@rAb@~@f@dA^r@^j@Zf@\\h@l@v@`@h@X^`@b@`@b@t@p@j@f@n@d@DBnAv@^TRJVLlAf@p@Vn@P`@Jz@P|BX~Cb@zAPTDb@Fb@F|AR`@FPBNBlEl@NBr@HdBTvEv@l@NNBt@R`@JD@VHf@P~An@t@`@v@d@hA|@dA|@r@n@tA~AVXV^`@j@b@p@p@nAR^h@jAd@dARd@Xt@`@lAZ`AVx@r@dCPr@f@xBzAtFbAvDfAnEfBhHBHf@jBf@nBNn@Nj@XfA`BpGnBxHzArF~AjGvC|K@FfC`KjBpHb@bBfAdEl@~BFTXhA`@~ANh@ZrA\\vAJn@X|APbAHn@Hj@LjAJx@HfAFn@Dn@FrAFvA@d@Bn@?@BpA@vA?tAA~@AlACnAGhBMbCUtDGbA?BEx@[fFIbBSnDi@fKQdDEx@Y|EEx@KlBMtBEr@Gz@KjBOdCKzAEv@Gx@YnEKxAKnAMxA]lCSdBe@bDS`B?@In@SlBADKz@Gn@?@]pCKz@CHWfBS|AKv@In@Gh@Eb@ATI|@Cr@Cr@A`@AZ?X?D?TAh@?j@@p@?^Bf@?@@^B`@Bd@B^Dd@F`@J~@@BHd@Jj@Lp@Jj@H^DTLl@Pp@J`@J^Nn@Lf@JZHXL`@N`@Th@JXT`@NZNXp@nA`@t@LVVd@LTR\\T^HNJPLRJPHPLVNVJRHTRf@Xp@Tl@Rh@FPv@zBhFvNj@zARn@|FhPRn@fBjFn@fBrAnDb@`A^|@Zp@R`@Zn@Xh@V`@Zj@Xb@Xb@TZV\\\\b@`@h@\\`@l@r@b@`@d@f@d@d@^Zd@^`@\\n@d@^VlAv@rAz@jAx@h@^JJ^XNNn@j@^^TXd@j@HLV\\Xb@R\\JNJPJTJNLZJTPb@Rf@Pd@Pl@Tr@Nh@Ll@@BJ`@Jh@FXBNF\\@D^vBPfATtAZjB`AzFhAvGdAdGpAzHx@rEt@nEh@|Cp@xDh@zCTlAx@pEPbA|@|E\\nBPfALbAFd@NtALnAPvBFbADd@HlA@VDb@@`@J|AHjAJ~AFz@@HDp@LrBT`E@Nl@fJN|B@PLbCJ|AFv@Dv@@JDj@LnBDh@N|BHpANnCf@nIFv@`@xG@^NfCDx@Dv@@RBb@?HBr@@r@?H?fA?^ALAn@Cd@ALAXG~@Ix@Ir@Kr@Mx@Mp@On@Sp@ERSn@aBpEIRi@zAk@zAUl@KXIP[z@O\\CHSd@MTOXQ\\CFSXCBMPMPEB_@d@UTKJWTwDzCYVEB_Av@}@v@OL]\\ONWVY\\GHQT[`@KNGHQZYd@GJa@v@a@~@Sf@GNK\\Un@Sp@Sr@Ol@S|@SfAKl@EXGj@AJGf@KfAGn@Cl@ANCh@ALAf@Ab@An@An@Ar@?B@p@?F?^@j@@^?XD~@Dp@Dp@Fp@Dh@Fd@Fj@Ht@Hf@Lv@Jh@Jj@@FXdB@BLr@XdB?BLt@ZfBLt@P~@`BjJlB~KjBnKx@bF@Db@~BHb@Lt@Jl@DVFX?@Lr@Jh@BJJl@?BFVDXF\\FZPt@Ln@Jb@TbAHZFVPt@J^Ld@Rr@Nh@J`@L`@Rt@HVJXPh@?@HVJZL^JVn@fB\\`A@BJXFN@DRj@Nb@L\\JZN`@L\\N`@Rf@Pf@DJPd@Rj@@BRl@Tl@DNHRL\\JZJTHTBHBHN`@Pf@Zx@Pf@FPFN@DL^JRPf@Tl@Nb@@BL\\Pd@p@fBDHBHRh@HTJTLZHRNd@Xt@Tj@Tj@Nb@LZb@fAN^BDVr@Vn@Rh@Rf@^`APb@JTFPPd@HRN^JZPf@Pj@Rh@\\hAj@dBPd@l@fBVz@Rj@Pd@JXHTN`@n@bBNb@DJ|@bCBFDHHTBHVp@L^N`@Nd@DLDNFPDLRt@Nn@Pt@RbABFTlABP@@Jn@BTDTDTD^BJ?DJp@Hn@?BFd@LlAFn@?@@JFf@Dr@BVB^?D@TBt@Bt@Bb@@x@@T@jABrADpEFvF@v@@p@?FBv@Bz@DnBDpBFpBDpBBx@@v@Bx@JxEJbEHjCNvEFdA^tJPdE@V@`@Bl@Bj@Dn@Bz@HvA@F?D@F?D@L@PRzE?FDfA@\\@^J~CBbADpAFnBDpBJtEBhBBlA@d@@b@Bn@@r@@b@@X?ZBf@@d@@`@@X@n@@bA?l@?p@?n@At@Af@?j@ATA\\AVA\\Cp@Ex@C`@C\\Cd@Gl@C^ALALAFAFADCHALALALCLANE\\EZGd@GZCNALCJ]zBaA|FoB`Mo@rDMp@o@nDe@dCUhAYtAc@hB_@`BYdAGXMd@Wz@IX_@pAa@rAADu@xBK\\M\\IVs@tBUl@Sn@w@~Be@pAk@dBu@|Bm@hBw@zBM^Qj@Un@Ur@Wt@Of@e@tACDSl@Sp@]bA_@hA_@hASl@IT_@lAGNo@lBa@nAABQh@Sj@Y~@Qh@Qd@ITIXIRoBdGUn@KZ[`Ai@|AK\\GNUl@[|@u@|BADQf@IVIXCHmBzFUr@[z@oAvDOb@Wx@[|@_@hAUn@Qf@KZO^i@~AiBpFAF?BABABAFGPq@tBuAbEu@zBYz@c@rAw@~Ba@pASl@sCxIUn@{@jCg@zAqAzDo@hBa@jAYv@Qf@Uh@CBO`@EHWj@ABUd@Wf@Wd@Ub@Wb@a@p@CDW^?@Yb@U\\[`@Y^Y^KLMNONKJY^[\\]\\YX]Z{@v@WP_@ZYRMHaBfAa@VaAp@_FfDwClBuClBeIpFk`@xWuA|@q@b@o@`@eG|D_@VeElCeAr@GDa@XkC~Aw@h@EDEDGFUPMHcBjAIFg@Za@XqBrAk@`@[RWP]T[RQLIDEBE?{CrBSNMHGDEDCBCBCBiNjJw@h@w@f@cEpC_An@a@X_@V_@VWPGDcC`B_@V_@VC@mAz@g@^i@`@_@X_@Zc@`@WVEBYVAB[X?@YXQNQPEDWVEDY^YZA@c@h@QRY\\KLMNORSVORKLMROPKLILEDA@SVQTOTCB[^Y^MPQPIJIHGHgCdDCFCBEFeErFiDnEsBjCqI~KgErFsAbBmClD_@d@Y\\e@n@QT[`@CBa@h@m@v@[`@EFkAxAe@n@mA|Aa@h@QRKJ_CxCwAjBINKNCDu@`A[`@]d@Y^]b@[`@UX{@lA[`@MNo@x@Yb@OPEDGHq@|@EFy@dACD[`@W\\[b@uAhBmClD[`@]b@MNMP]d@[^[b@uAfBc@h@qBhCq@r@SXqRfW}JlM_AnAy@fAuAfBiB`C}GzI[b@_BrB}@nAmA`BoBjCuD|E?@[`@gErF_@h@o@z@cB|B[b@[`@w@fASX_ApA?@Yb@A?iCtDGHSXc@n@cAvAEH[b@m@|@IJ[b@[b@aE|FiAbB_@l@CBOVEHILc@t@Yl@CFWh@?@Yn@i@tASj@ITYx@i@pBg@fBwAjFIVgAbEcClJsBjIQp@Ol@aBnGCHk@tBkBdHgAzDADu@hCM\\Q`@]z@g@bAi@`Ak@~@i@t@Y^{@bA}@dA_@Z_@\\]\\EDIH}@z@w@n@{A`AoBtAo@f@}@p@_CzB_@^oBbCg@n@u@`AsAfBk@x@cBnCQXs@lAEH_BnCOTKNgB~CqAbCA@cB~C_BxCwCrFwB~DgClEkBdD}@|Ae@v@kAtB}CnFcGjKGJ_BpCUb@qBnDQZ}DbHQX}@`BcBzCWd@Wd@GLeA`BaAbBeA`BGHcBtBQN}@|@yBvByD|CuDtC_E`DeA`AuFhFQNKL_@^eFnFe@h@]^_BfBoB~BoBrBmBxBeAlA_BbCwAvBwBxDqAhCyBzEEJWj@k@xAi@nAWt@Ul@CHk@hB[`ACHADw@jC?BQj@a@~Ag@tBmA|ECP_ApDGTOp@Qr@]xACHc@nB]`Ba@nCKz@Ip@MfBARGv@c@xGMnBGv@Gt@[bF]tGc@xGOhDMvAQzAQjA_@pBCLQp@Mf@c@zAk@zAUd@O`@OV]f@o@x@i@n@w@p@eA|@{@v@_DjCyD|C{ChCy@z@y@~@m@p@m@v@u@~@a@p@yAhCiAbCuDrIcD~GyBzEkBdEuCpG_A~BsAvC}@jBy@jBkBxC{@lA{@jA}A|AcBxAsFlE_CjB}BjBeCvBqMrKcDhCyL~JuAhAIF{ChC_@XuAjAu@p@cF`EsFrEc@^gAbA_AlAwAhBe@p@Yf@a@n@{@`Bc@x@Wn@i@nAA@Qn@IXIT[jAGVOp@I\\aAdFOhAQhAmA`I?@kBpMSrBOpAmAlRo@xKATY`FK`BU|DWvCShBAL]zASbASz@AD_@rAO^Qf@MZKT_@v@s@dA_ArAKNA@cDbEGF_BbCy@vAABYp@Sb@g@vAKX}@tC_CfHWx@Sn@gCjI}@nCg@|AaAtDGZm@fE"
                     },
                     "start_location" : {
                        "lat" : 51.1115467,
                        "lng" : -114.6434838
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 433
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 33
                     },
                     "end_location" : {
                        "lat" : 51.2093551,
                        "lng" : -115.5373155
                     },
                     "html_instructions" : "Take the exit toward \u003cb\u003eBanff Town Ville\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eTunnel Mountain\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eMont Tunnel\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "kwpwH`uc`UIJABA@?DCLARK|AMbBGdACr@ClAAh@?t@?p@@`@?P?VA`@AxAG|@GdA?`B?d@Bp@?b@HdA"
                     },
                     "start_location" : {
                        "lat" : 51.2090213,
                        "lng" : -115.5312081
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 1024
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 65
                     },
                     "end_location" : {
                        "lat" : 51.200209,
                        "lng" : -115.5375983
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eBanff Ave\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eLake Minnewanka Scenic Dr\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Banff Ave\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "oypwHf{d`UFZjBCb@?b@AxAAb@?nAAbCBvE?hA?pDAbBBjBDfJLN?zFJ"
                     },
                     "start_location" : {
                        "lat" : 51.2093551,
                        "lng" : -115.5373155
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "5.3 km",
                        "value" : 5320
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 381
                     },
                     "end_location" : {
                        "lat" : 51.1847462,
                        "lng" : -115.547679
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eTunnel Mountain Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "i`owH~|d`U@i@?QAgBAaA?y@AqB?sBA}BAeAGiAMgAO{@Mg@a@_BUs@So@}@kCSo@Uo@w@cCo@cBUm@Um@Uk@Um@Um@Um@Qe@[q@Wi@gAaCWi@M[EQQq@AEAk@?[Da@BEDYLUDKNUBAROLABAP?L@D?\\H`@Hb@Hb@J`@HfATb@@VBJA\\CDAv@KVKTQHETU\\_@VYt@wAJS\\iA|@gFNgAR{ATkANa@BIFSLWFM\\e@|@aA`@g@h@gATgABKJu@?ENiBHcATiAFOLa@Po@z@qABCh@k@pBcB|AsAxAoABA~BiBd@_@|@c@VMl@EfAIb@Cb@C|Gc@b@CfAGb@CHATBTDNHNFXVPZZb@Rb@BFFZNhA@T@f@LvDXvFPrD@`@Bx@FxBJrBVzCJr@h@`EJlB@`@?r@AZC^KjASbBo@fDm@|CMr@Kf@O~@Kl@Ep@Cb@@b@BbCFxC@x@Bv@@x@FdCPnBLzAf@~C`AtD`@nARn@r@xBpAxGNr@Lr@H`@nAlGLr@HZRjAzAbIHh@~ArJv@bE`@pBHZXfAJX\\x@N^Tj@BFNd@L^b@lAJ^Vx@VjAT`B"
                     },
                     "start_location" : {
                        "lat" : 51.200209,
                        "lng" : -115.5375983
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "ykeyHrtkoThMoKjGgHlD_Ak@aOf@mLpCsMjF{S`Vc`@tCga@f@{y@yO}uA}@am@mEuz@^qv@jOfBfB}AnHsKbZF~CkHnBeL~Pca@nAsC~No@dd@HpMMvDdClb@`k@tKx@jJInG_ApMlCbObFbRtQnh@zk@|Tps@tDz}@BppBB`{BBhyFC|nIpBjo@tWbk@rNdMnW`B~^VhKfBzTtLv[vf@~Lpj@`Cpl@AnbCG|tFDnlBqCheBoPx|@}Bf_Bp@bl@hFv\\nMnk@xBjY?jcAWdgIMvfI@nyT?jjb@AvcDBneDr@t]ve@tc@hbAdgAfVr\\jm@poAtgA`}BzUdg@d\\~b@d_@lO`hEx@dvBNxg@x@rOfLjJ~UbC|e@r@`pBlJ`c@lSdWpGlCh[xB|m@Mp_@T|JzCnOfThPtz@|RbhAzGxS~IjKv}@ff@br@fm@fM`HGlyBA`dE?t`GGtaLFrrGQnnN@lbG|@|BlDeBtK{Elg@eAx{Bv@fQlDjGdL~HdVbDd`@dBzsDvM`gBqGbwCz@xk@fHvc@rQjb@bYhWjVrPvWr]lQje@`Jnf@lD`o@e@ddBvI~lFpIlp@hSbc@j[|[zQfg@zSdw@vRp\\rPdOnLrF`XrDdXyClUeLfTuRrMgGvN@zYxT~PjP~S~LhPfClSxL|D`Mj@hXp@tUqCvKe@vAp@bAdDlEz@zqAK~_LAvxN@xgC|@nz@vDzb@`Dnl@_@zkAuAlvDuCzgFs^jtAOr`@lGbm@`Ebi@[vg@qGri@mTneA_]taB_v@btD_UvfA}k@loBowAx{Eo\\~hAy}@tuCar@pmAaW`g@gGbn@xHfnBdQ`iAhe@fnBdIji@pB`d@dKxlClInqBdSjvAv[psCpi@zsFvPbdBfKdb@zeAjrDnuBbjHf\\tcAhRnPxXpEba@pK~Ql[xZdlAzXrhArBp]mLzqB_Glr@~Kpc@~f@zpAhb@xb@~FvMdMbt@jOx_AfDdi@pF|iA{Ix]gFvJuPrOiH~RChf@zT`qAtZl`Afb@|jAvEha@rEzdBvBvz@gBd[mObz@}Mxa@kXjy@yz@bcCa~AxiAmg@x\\mq@hf@mR~U{aB~wBe|AzqB_Vl]yKn[eY~cAsVtV_]|d@kn@phAw\\vi@{v@fu@sXnj@uLjf@_Hz_A{DbOqIrJ{VxU{[fr@mQ`[kw@to@ah@pg@}Jlc@aMhtA_Rn[eTbt@s@jWDbM|UE`a@GI_TgLca@kFyRdJApEk@rFsNxH}TvCoLzPcNdWKfEpj@PpR}CdRn@bVbIx^pOnv@lDnM"
         },
         "summary" : "AB-9 W and Trans-Canada Hwy/AB-1 W",
         "warnings" : [],
         "waypoint_order" : []
      }
   ],
   "status" : "OK"
} '''
  

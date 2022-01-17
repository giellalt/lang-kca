
# K H A N T Y   D I S A M B I G U A T O R          

**Nore!** Some tag declarations or sets may be left from copying this file from sma.





## Delimiters , tags and sets


DELIMITERS = "<.>" "<!>" "<?>" "<...>" "<¶>"; #@CODE DELIMITERS = "<.>" "<!>" "<?>" "<...>" "<¶>"; # @CODE


## Tags and sets 



### Tags declared as single-membered LISTs 

* LIST N = N ; #@CODE@
* LIST Sg = Sg ; #@CODE@
* LIST Pl = Pl ; #@CODE@
* LIST Nom = Nom ; #@CODE@
* LIST Acc = Acc ; #@CODE@
* LIST Gen = Gen ; #@CODE@
* LIST Par = Par ; #@CODE@
* LIST Loc = Loc ; #@CODE@
* LIST Abl = Abl ; #@CODE@
* LIST Lat = Lat ; #@CODE@
* LIST Tra = Tra ; #@CODE@
* LIST PxSg1 = PxSg1 ; #@CODE@
* LIST PxSg2 = PxSg2 ; #@CODE@
* LIST PxSg3 = PxSg3 ; #@CODE@
* LIST PxDu1 = PxDu1 ; #@CODE@
* LIST PxDu2 = PxDu2 ; #@CODE@
* LIST PxDu3 = PxDu3 ; #@CODE@
* LIST PxPl1 = PxPl1 ; #@CODE@
* LIST PxPl2 = PxPl2 ; #@CODE@
* LIST PxPl3 = PxPl3 ; #@CODE@
* LIST V = V ; #@CODE@
* LIST Prs = Prs ; #@CODE@
* LIST Prt = Prt ; #@CODE@
* LIST Sg1 = Sg1 ; #@CODE@
* LIST Sg2 = Sg2 ; #@CODE@
* LIST Sg3 = Sg3 ; #@CODE@
* LIST Du1 = Du1 ; #@CODE@
* LIST Du2 = Du2 ; #@CODE@
* LIST Du3 = Du3 ; #@CODE@
* LIST Pl1 = Pl1 ; #@CODE@
* LIST Pl2 = Pl2 ; #@CODE@
* LIST Pl3 = Pl3 ; #@CODE@
* LIST Inf = Inf ; #@CODE@
* LIST Neg = Neg ; #@CODE@
* LIST ConNeg = ConNeg ; #@CODE@
* LIST Foc/gan = Foc/gan ; #@CODE@
* LIST PrfPrc = PrfPrc ; #@CODE@
* LIST PrsPrc = PrsPrc ; #@CODE@
* LIST VGen = VGen ; #@CODE@
* LIST Ger = Ger ; #@CODE@
* LIST Ind = Ind ; #@CODE@
* LIST Imp = Imp ; #@CODE@
* LIST ImpII = ImpII ; #@CODE@
* LIST Pot = Pot ; #@CODE@
* LIST Cond = Cond ; #@CODE@
* LIST Imprt = Imprt ; #@CODE@
* LIST IV = IV ; #@CODE@
* LIST TV = TV ; #@CODE@
* LIST Opt = Opt ; #@CODE@
* LIST Actor = Actor ; #@CODE@
* LIST Clt = Clt ; #@CODE@
* LIST A = A ; #@CODE@
* LIST Pos = Pos ; #@CODE@
* LIST Ord = Ord ; #@CODE@
* LIST Coll = Coll ; #@CODE@
* LIST ABBR = ABBR ; #@CODE@
* LIST ACR = ACR ; #@CODE@
* LIST Comp = Comp ; #@CODE@
* LIST Superl = Superl ; #@CODE@
* LIST Attr = Attr ; #@CODE@
* LIST Pron = Pron ; #@CODE@
* LIST Pers = Pers ; #@CODE@
* LIST Dem = Dem ; #@CODE@
* LIST Interr = Interr ; #@CODE@
* LIST Rel = Rel ; #@CODE@
* LIST Po = Po ; #@CODE@
* LIST Pr = Pr ; #@CODE@
* LIST Adv = Adv ; #@CODE@
* LIST Interj = Interj ; #@CODE@
* LIST Indef = Indef ; #@CODE@
* LIST Num = Num ; #@CODE@
* LIST Prop = Prop ; #@CODE@
* LIST Mal = Mal ; #@CODE@
* LIST Fem = Fem ; #@CODE@
* LIST Sur = Sur ; #@CODE@
* LIST Org = Org ; #@CODE@
* LIST CS = CS ; #@CODE@
* LIST CC = CC ; #@CODE@
* LIST Pcle = Pcle ; #@CODE@
* LIST CLB = CLB ; #@CODE@
* LIST LEFT = LEFT ; #@CODE@
* LIST RIGHT = RIGHT ; #@CODE@
* LIST COMMA = "," ; #@CODE@
* LIST Der1 = Der1 ; #@CODE@
* LIST Der2 = Der2 ; #@CODE@
* LIST Der3 = Der3 ; #@CODE@

### Semantic tags

* LIST Sem/Ani = Sem/Ani ; # 
* LIST Sem/Fem = Sem/Fem ; # 
* LIST Sem/Mal = Sem/Mal ; # 
* LIST Sem/Obj = Sem/Obj ; # 
* LIST Sem/Org = Sem/Org ; # 
* LIST Sem/Plc = Sem/Plc ; # 
* LIST Sem/Sur = Sem/Sur ; # 
* LIST Sem/Time = Sem/Time ; # 
* LIST Sem/Hum = Sem/Hum ; # 
* LIST Sem/Date = Sem/Date ; # 
* LIST Sem/Year = Sem/Year ; # 
* LIST Sem/Group = Sem/Group ; # 
* LIST Sem/Route = Sem/Route ; # 
* LIST Sem/Build = Sem/Build ; # 
* LIST Sem/Place = Sem/Place ; # 
* LIST Sem/Food = Sem/Food ; # 
* SET FIRSTNAME = (Prop Sem/Fem) OR (Prop Sem/Mal) ; # 

### Syntactic tags

* LIST @CNP = @CNP ; # 
* LIST @CVP = @CVP ; # 
* LIST @+FAUXV = @+FAUXV ; # 
* LIST @+FMAINV = @+FMAINV ; # 
* LIST @-FAUXV = @-FAUXV ; # 
* LIST @-FMAINV = @-FMAINV ; # 
* SET MAINV = @-FMAINV OR @+FMAINV ; # 
* LIST @ADVL = @ADVL ; # 
* LIST @>ADVL = @>ADVL ; # 
* LIST @ADVL< = @ADVL< ; # 
* LIST @<ADVL = @<ADVL ; # 
* LIST @ADVL> = @ADVL> ; # 
* LIST @-FADVL = @-FADVL ; # 
* LIST @A< = @A< ; # 
* LIST @>A = @>A ; # 
* LIST @ActioN> = @ActioN> ; # 
* LIST @APP = @APP ; # 
* LIST @APP-N< = @APP-N< ; # 
* LIST @APP-Pron< = @APP-Pron< ; # 
* LIST @APP>Pron = @APP>Pron ; # 
* LIST @APP-Num< = @APP-Num< ; # 
* LIST @APP-ADVL< = @APP-ADVL< ; # 
* LIST @CMPND = @CMPND ; # 
* LIST @COMP-CS< = @COMP-CS< ; # 
* LIST @HAB = @HAB ; # 
* LIST @INTERJ = @INTERJ ; # 
* LIST @MEASURE = @MEASURE ; # 
* LIST @>N = @>N ; # 
* LIST @N< = @N< ; # 
* LIST @NNum> = @NNum>; # 
* LIST @NumN< = @NumN<; # 
* LIST @>Num = @>Num; # 
* LIST @Num< = @Num< ; # 
* LIST @NPron< = @NPron< ; # 
* LIST @NQ< = @NQ< ; # 
* LIST @NUM-PRON = @NUM-PRON ; # 
* #LIST @NUMBER = @NUMBER ; # 
* LIST @OBJ = @OBJ ; # 
* LIST @<OBJ = @<OBJ ; # 
* LIST @OBJ> = @OBJ> ; # 
* LIST @OPRED = @OPRED ; # 
* LIST @<OPRED = @<OPRED ; # 
* LIST @OPRED> = @OPRED> ; # 
* LIST @PCLE = @PCLE ; # 
* LIST @HNOUN = @HNOUN ; # 
* LIST @PrcN> = @PrcN> ; # 
* LIST @PronN< = @PronN< ; # 
* LIST @PronN> = @PronN> ; # 
* LIST @Pron< = @Pron< ; # 
* LIST @>Pron = @>Pron ; # 
* LIST @P< = @P< ; # 
* LIST @>P = @>P ; # 
* LIST @SPRED = @SPRED ; # 
* LIST @<SPRED = @<SPRED ; # 
* LIST @SPRED> = @SPRED> ; # 
* LIST @SUBJ = @SUBJ ; # 
* LIST @<SUBJ = @<SUBJ ; # 
* LIST @SUBJ> = @SUBJ> ; # 
* LIST @SUBJ-QH = @SUBJ-QH ; # 
* LIST @TITLE = @TITLE ; # 
* LIST @VOC = @VOC ; # 
* LIST @X = @X ; # 



### Sets

#### Grammatical sets

* LIST CASES = Nom Acc Gen Par Loc Abl Lat Tra ; # 
* LIST ADVLCASE = Loc Abl Lat Tra ; # 
* LIST NUMBER = Sg Du Pl ; # 
* LIST WORD = N A V Adv Pron Interj Num CS CC Pcle Pr Po ; # 
* SET REALWORD = WORD - Num - Ord ; # 
* SET REALWORD-NOTABBR = WORD - Num - Ord - ABBR ; # 


#### Sets for NP identification

* LIST NOT-ADV-INT-PCLE = N A Num Pron A V CC CS ; # 
* SET NOT-ADV = WORD - Adv ; # 
* SET NP-HEAD = Num OR N OR Pron ; # 
* SET PRE-NP-HEAD = (Prop Attr) OR (Prop @>N) OR (A Attr) OR (ABBR Attr) OR (Pron Pers Gen) OR (Pron Logo Gen) OR (N Gen) OR Num OR (Cmpnd) OR CC OR (Pron Dem) OR (Pron Refl Gen) OR (Pron Indef) OR (PrfPrc @>N) OR (PrfPrc @>N) OR (PrsPrc) OR (A Ord) OR Attr ; # 
* SET NP-MEMBER = PRE-NP-HEAD OR N ; # 
* SET NPNH = WORD - PRE-NP-HEAD OR (ABBR) ; #  NPNH  = "NOT-PRE-NP-HEAD" 
* SET NPNHA = WORD - PRE-NP-HEAD OR (ABBR) OR Adv ; # 
* SET NPNHAI = WORD - PRE-NP-HEAD - Adv - Indef ; # 


#### Noun sets

* SET PX = PxSg1 OR PxSg2 OR PxSg3 OR PxDu1 OR PxDu2 OR PxDu3 OR PxPl1 OR PxPl2 OR PxPl3 ; # 

#### Verb sets

The set REALCOPULAS is smaller than COPULAS, made for verbs with PrfPrc complements: Seammás REALCOPULAS son dovdan iežas...
* LIST REALCOPULAS = "lea" ; # 

The set COPULAS is for predicative constructions
* LIST COPULAS = REALCOPULAS ; # 
* SET V-NOT-COP = V - COPULAS ; # 

Verbs that never have arguments of their own 

These verbs can take arguments, so they do not belong in the AUX group, 
but they are nevertheless mapped to (@+FAUXV). 

* SET AUX = COPULAS OR Neg ; # 
* SET VFIN = Ind OR Imprt ; # 
* SET VFIN-NOT-AUX = VFIN - AUX ; # 
* SET V-MAIN = V - COPULAS - Neg ; # 
* SET VFIN-NOT-NEG = VFIN - Neg ; # 
* SET NOT-NP = VFIN-NOT-NEG OR ConNeg OR Inf OR Pcle OR Interj OR CS ; # 
The set NP-BOUNDARY is bigger. 



#### Boundary sets

Empty for now.



## Disambiguation rules


### BEFORE-SECTIONS


**Rule: Date1** for adding Sem/Date as a tag to readings which looks like dates.
**Rule: Date2** for adding Sem/Date as a tag to readings which looks like dates.
**Rule: Date3** for adding Sem/Date as a tag to readings which looks like dates.
**Rule: Date4** for adding Sem/Date as a tag to readings which looks like dates.


### SECTION

### Cycle 0: No context around the target word

Still no rules written. 



### Cycle 1: Local context around the target word

**Rule: Attr** removes Pos and keeps Attr for A in front of A or N.

**Rule: Pos** removes Attr and keeps Pos for A if no .



### Cycle 2: Slightly less local context

Still no rules written. 


### Cycle 3: Global disambiguation 
Still no rules written. 
### Cycle 4: Syntactic disambiguation 
Still no rules written. 
### Cycle 5: Post-syntactic morphological disambiguation
Still no rules written. 



* * *
<small>This (part of) documentation was generated from [../src/cg3/disambiguator.cg3](http://github.com/giellalt/lang-kca/blob/main/../src/cg3/disambiguator.cg3)</small>
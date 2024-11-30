java c
ECON3173 – Cross Section and   Panel   Data Analysis
Individual Project: Guidelines and   Questions
This document provides guidelines and questions for the Individual Project of   ECON3173,   which accounts for 40%   of   the total   marks.Honoring the   precepts   of academic   integrity   and   applying   its   principles   are   fundamental   responsibilities   of all   students   and   scholars   at   UIC.   You   are   advised   to   read   through   the   ‘UIC   Guidelines   for   Handling   Academic   Dishonesty’   file   on   iSpace   before   you   start   your assignment. Any form. of   plagiarism or cheating can result in various disciplinary and   corrective   activities. Using   generative   AI   tools   is   not   allowed.
Deadline: by 20/12/2024.   Submission Method:
a)          Please       submit      your      typing      assignment      report      in      a      single       PDF      file      to      Turnitin   ‘Submission   Link:   Report’via   iSpace.   The   filename   of   your   PDF   submissions   should have      the      following      format:   ECON3173_Project_Student      ID_Name      in      Pinyin         (e.g.,   ECON3173_Project_190000001_Mi   Lin).
b)          Save          your          data             and          .do          file(s)             in          a             zip          file.          Name             your          zip          file             as   ECON3173_Project_Student ID_Name in Pinyin. Then, upload your file to‘Submission   Link:    Stata    Data    and    Program’via    iSpace.    You    are    expected    to    submit    2    .do    files,
namely   ParA.do   and   PartB.do,   respectively,   should   be   able   to   replicate   each   part   of   your submitted work.
c)          Use   the   ‘ECON3173_Individual    Project_Report   Template’   file   on   the   iSpace   to   input   your report.   Ensure you provide a question   number   for   each   part   of   your work.
Format Requirements
Cover page:
Please   input   your   name   and   student   ID   on   the   top   of the   cover   page   of   the report template, which is   available on   iSpace.
Word limit:The    required    minimum      word       count    is       1,500    words,      with      a   maximum   of 2,000 words   in total,   excluding tables,   graphs,   and   appendices.
Referencing:Your      report      should      include      appropriate      references      in    APA   format   to   avariety   of   necessary   literature   sources   and   a   wide-   ranging bibliography of academic aspects of economics.
Font /   Size:
Cambria   12 or Times   New   Roman   12.
Spacing /   Sides:
1.0 / Single-sided / Single-line spacing between two paragraphs.
Pagination required:
Yes
Margins:
At   2.50 to both left and right,   and   ‘justified’   .
Part A: Imitate an existing research   (30%)Traffic crashes are the leading cause of   death for Americans between the ages of 5 and 32.   Through   various    spending    policies,    the    federal    government    has    encouraged    states    to   institute mandatory seat belt laws to reduce the   number   of fatalities   and   serious   injuries.   In   this   exercise,   following   Einav   and   Cohen   (2003),   you   will   investigate   how   effectively   these   laws   increase   seat   belt   use   and   reduce   fatalities   using   the   “SeatBelts.dta”   dataset   posted   on   iSpace.   The   data   file   Seatbelts   contains   a   panel   of data   from   50   U.S.   states   plus   the       District       of         Columbia          from       1983         through          1997.          The       dataset       is          detailed       in   “Seatbelts_Description.pdf”.    It    was    used    in   the    Einav    and    Cohen    (2003)    paper,    which   serves   as the background   reading   for this   exercise.       Both   files   are   available   on   iSpace   as   well.
A1.          Using       OLS      to      estimate      the      effect      of    seat       belt      use      on      fatalities      by      regressing   fatalityrate   on   sb_useage,   speed65,   speed70,   ba08,   drinkage21,   ln(income),   and   age.   Does   the   estimated   result   suggest   that   increased   seat   belt   use   reduces   fatalities?   Report, interpret, and   comment on your results.   (5%)
A2.          Run    a    one-way    fixed    effect   model   with   state-fixed    effects.    Do   the   results    change   when you add state-fixed effects? Run a   two-way   fixed   effects   model with   both   time   and   state-fixed   effects.   Do   the   results   change   when   you   add   time-fixed   effects   plus   state-fixed   effects?   Report, interpret, and   comment on your results.   (5%)
A3.          Which    regression    specification    you    obtained      from    A1      and    A2      is      most      reliable?   Explain why.   (5%)
A4.          Using   the   results   from   the   two-way   fixed   effects   model   with   both   time   and   state-   fixed effects, discuss the magnitude of   the coefficient on sb_useage. Is it large? Small?   How    many    lives    would    be    saved    if    seat    belt    use      increased      from      52%    to      90%?   Illustrate your calculation and   comment on your result.   (5%)
A5.          There      are      two      ways      that      mandatory      seat      belt      laws      are       enforced:      “Primary”   enforcement   means   that   a   police   officer   can   stop   a   car   and   ticket   the   driver   if the      officer    observes    an    occupant    not    wearing    a    seat    be<    “secondary”      enforcement      means that a police officer can write a ticket if   an occupant is not wearing a seat belt,      but   must   have   another   reason   to   stop   the   car.   In   the   data   set,   primary   is   a   binary      variable   for primary   enforcement,   and secondary is   a binary variable   for   secondary      enforcement. Run a regression of   sb_useage on   primary,   secondary,   speed65,   speed70,      ba08,   drinkage21,   ln(income),   and   age,   including   fixed   state   and   time   effects   in   the      regression.    Does    primary    enforcement    lead    to    more      seat    belt      use?    What      about      secondary enforcement?   Report, interpret, and comment   on your   results.   (5%)
A6.          In   2000, New Jersey changed from   secondary   enforcement   to   primary   enforcement.   Assume   that   data   availability   is   not   an   issue,   design   a   Differences-in-Differences   estimation   strategy   to   estimate   the   number   of   lives   potentially   saved   per   year   by   making this change.   Explain your approach.   (5%)
Part B: A small-scale research project –   innovation   (70%)   Introduction:In this project, you are invited to empirically investigate potential causality between firms’   business      environment      and      economic      performance      using      a      firm-level      dataset      from      economies      included      in      the      World      Bank      Enterprise      Survey      Data      (WBESD).      WBESD      database   collects information about an economy’s business   environment,   how   individual      firms    experience    it,      how      it      changes      over      time,      and      the      various      constraints      to      firm      performance and growth, etc. The entire database is available to researchers and includes      all questions from the surveys   at   the   firm   level.
Guidelines to download and prepare data for   this   individual   project:
a)       Please   visithttps://login.enterprisesurveys.org/to   register   your   user   account   for   the   WBESD database   (see the snapshot below).   Registration is   free.
   
b)      There   are   a total   of 97   economies   represented   in the World   Bank   Enterprise   Surveys   Database   (WBESD).   Among   these,   61   economies   have   a   time   span   of   at   least   th代 写ECON3173 – Cross Section and Panel Data Analysis
代做程序编程语言ree   years.   For their   individual   projects,   students   are   required   to   select   data   from   a   panel   of random combinations of   three different economies   out   of   these   61   economies.Data allocation protocol:   Students are required to pick   a   lottery   ticker   number   first.   An   “Individual   Project   Lottery Ticket Sign-up   Sheet” will be available in   iSpace   from   9   p.m.   on   Tuesday,   26/11/2024.   Please   sign   up   for   a   lottery   ticket   number   by   12   noon   on Wednesday,   27/11/2024. We will operate on a   'first-come,   first-served'   basis.
A   lucky   draw   will   be   conducted   in   class   on   Thursday,   28/11/2024,   to   assign   specific   economies to each lottery ticket   number.
c)       Once registration is completed, login and download the data following the steps below:
i.             Login with yourusername and password. You will   be   directed   to   the ‘Full   Survey Data’ page.
ii.             Select ‘Panel data’ under ‘Survey Type’   on   the   left.   Ensure   you   are   on   the ‘Data   by   Economy’ view instead   of   ‘Combined   Data’   .   See the snapshot below.
iii.             Download    your    economies’    corresponding    data   and   documentation   for   all   the   available years.
For example, Afghanistan has two panel data files,   one   for   2005   and   2009   and   the   other for   2008,   2010, and   2014. Then   download both   of   them.
iv.             Extract the data and survey documentation files into   a working folder   on your   PC.   Now the   data file is   ready to   open   in   Stata.
   
Answer ALL of   the Following Questions
Note   that   this   is   not   an   essay-type   assignment.   Please   answer   the   questions   one   by   one.   For each question, the performance   of   the   Stata   do files   accounts   for   20%   of   the   marks.
B1)       Use the Stata command “append”   to   append   data   of   all years   and   economies   into   a   single Stata data file with panel data   format.   Select   and   rename variables   in   Table   1.   ‘Old   name’   refers   to   the   variable   name   in   the   original   dataset,   while   ‘New   name’   is   the   new    corresponding   name   to   be    defined.       Generate    a    new    variable    exp_dum   (export    dummy)    equals    1    if   sales_exp    is    positive;      otherwise,      0.      Generate      a      new   variable foreign_dum    (foreign    ownership    dummy)    equals    1   if   foreign   is   positive;   otherwise, 0. Generate a new variable soe_dum   (state ownership dummy)   equals   1   if   soe is positive;   otherwise,   0.   (5%)
Table   1: Variable List
Survey Questions
Old   name
New name
GENERAL INFORMATION
   
   
Year the survey was   conducted
year
year
Panel   ID   (the same   ID for each firm   across   different years)
panelid
panelid
What percentage of   this firm is   owned by the   Government/State   %
b2c
soe
What       percentage          of       this       firm          is       owned          by       Private          foreign   individuals,   companies, or organizations %
b2b
foreign
SALES
   
   
During    the    past    fiscal    year,      what    was      this      establishment’s      total   annual sales?
d2
sales
During the past fiscal year, what percentage of   this   establishment’s   sales were:   Direct exports   %
d3c
sales_exp
LABOUR and CAPITAL
   
   
Total   number    of   permanent,   full-time   workers   at   the    end    of   last   fiscal year
l1
employeesDuring   the   past   fiscal   year,   what   was   the   net   book   value,   i.e.,   the   value      of    assets      after    depreciation,       of    the      following:       Machinery,   vehicles, and   equipment
n6a
capital
Cost of raw materials   and intermediate goods used in   production   in   the last   fiscal year
n2e
materials
BUSINESS-GOVERNMENT RELATIONS
   
   In   atypical week   over the   last   12   months, what   percentage   of total senior    management’s    time   was    spent    dealing    with    requirements   imposed by government regulations? %
j2
reg_timeOver       the       last          12       months,       has         this          establishment       secured          a   government    contract    or   attempted   to    secure   a    contract   with   the   government? Yes/No
j6a
gov_contractB2)       Conduct   exploratory   data   analysis   for variables listed   in   B1),   i.e.,   using   appropriate   summary   statistics   (e.g.,   observation   number,   mean,   standard   deviation,   minimum   and   maximum   values,   etc.)   to   explain   your   data   and   make   necessary   comments.                       (10%)Considering   total    output   is    measured   by   Sales,   labour   input   is   measured   by   the   total   number      of    employees,       capital      is      measured      by      capital,      and      intermediate      inputs      are   measured by materials, a production function   can be   written   as:
sales   = Acapitalα   Employeesβ   Materialsy                                                                                                                                                                                       (1)
where A   is the total   factor   productivity   (TFP).   Based   on   panel   data,   taking   logarithms   on   both sides,   equation   (1) is transformed to
ln(salesit   )   =   ln(A)   + α ln(capitalit   )   + β ln(Labourit   )   + y   ln(Materialsit   )   + eit                                 (2)
B3)       Based    on   the   variable   ‘panelid’,    set   the   dataset   in   a   panel   format,   then   obtain   the   estimated   coefficients   in   equation   (2)   by   running   panel   data   regression.   Comment   on    your    results,    including    a)    a    discussion      on      the      capital,      labour,      and      materials   elasticities   of sales,   respectively,   and   b)   a   comparison   between   the   panel   two-way   fixed   effect and random effect   model.   (10%)B4)       Include    Export_dumit          as a new variable of   interest in equation (2) to test if   a firm’s         performance   improves   after   entering   export   markets.   Based   on   relevant   economic         theories   or   literature,   explore   the   data   set   to   add   appropriate   control   variables   to         the production equation   (2). Run a panel regression and interpret the results.   (10%)
B5)       To   what   extent   could   we   use   the   estimated   coefficient   on      Export_dumit            obtained in   B4)   for   causal   inference?   Explain.   Illustrate   an   appropriate   empirical   strategy to   make   improvements   if   deemed   required.   Finally,   reestimate   the   model   based   on   your proposed empirical strategy, compare the results to what you have obtained in   B4, and   comment on the   results.   (10%)B6)       Explore   the   complete   data   set   (i.e.,   do   not   have to   be   limited   to   the   variables   listed      in B1) and design an empirical   model to   evaluate   the   impact   of ownership   structure      on the export decision. Interpret and comment on the empirical results   you obtained.       (10%)
B7)       Predict    firm-level    productivity    (i.e.,      ln(A)   +   eit   )   to   test   the    hypothesis   that   good   business-government   relations   boost   productivity.   Explore   the   complete   data   set   (i.e.,   do not have to be   limited   to   the   variables   listed   in   B1)   to   propose   an   empirical   model with   an appropriate   empirical   strategy based   on   relevant   economic theories   or    literature.    Explain    the    variable(s)    you    select    for    this    question.    Interpret    and   comment on the   empirical results you obtained.   (15%)





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com

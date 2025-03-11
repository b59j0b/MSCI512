java c
MSCI512: Simulation   and   Stochastic   Modelling
2024/25 Coursework   Task
Task instructions (please   read   carefully)
•         The   coursework   consists   of three   problems that   require the   application   of   stochastic   modelling or   simulation.
•          Provide an answer for   all   three   problems.
•         The   maximum score   is   100:
•          Question   1   is worth   25   marks
•          Question   2   is worth   20   marks
•          Question   3   is worth 45   marks
•         A further   10   marks will   be awarded for the clarity   of the   report   writing.
•         You are expected to use appropriate software (e.g.   Microsoft Excel,R, Python, Simul8)   to   help you answer the   questions.
•         This   coursework   is   related to   all   parts   of the   module.    You   may   use   any   method from   the course to approach the   problems.
•          For all questions describe   and justify the   assumptions you   are   making   with your   model, as well as   any   potential   limitations.
•         When providing a numerical answer   that does not involve   a   confidence    interval,   report   it correct to at least 3 significant figures.    Also,   when   using   non-exact   numbers   obtained from aprevious calculation, make sure these numbers are   correct to   at   least
3 significant figures.
•         This   coursework   is to   be   done   as   part   of   a group   of   two   or three. Collusion   between   groups and plagiarism are regarded as serious offences   and will   be   penalised   severely.   Information about the university’s    plagiarism framework   can be found       here:   https://modules.lancaster.ac.uk/mod/resource/view.php?id=1384800   .
Submission instructions
•         The deadline for submission   is 9:00AM on   March   24th   2025.
•         Only one   member of the group   is   required to   make the submission.
•         Your   answers   to   the   questions   can   be   either   typed   (e.g.   using   Microsoft   Word)   or   handwritten and   scanned.
•         You   should   include   full   details   of   your   methods   in   your   answers.       If   you    calculate   answers by hand, you should include all of   your calculation steps.    If you use   computer   software (e.g. spreadsheets, computer programs) you should include the relevant files   (e.g.   .xlsx,   .py,   .txt,   .s8)   in your submission.    Please also   include   enough   explanation   in   your answers to   make   it clear what you   are   doing   and why.
Question   1   [25   marks]
A call centre operates 24   hours   a   day,   7   days   a   week.   When   a   customer   calls,   they   wait   for one   member of staff to take their call.   All   members   of   staff   are   cross-trained   and   so   are   able   to   handle all   parts of the enquiry.   After the   enquiry   has   been   fulfilled,   the   call   ends   and   the staff   member   is free to take the   next call.
The staff all work   in 8-hour   shifts   in the   following   pattern:
•         6am   - 2pm
•         2pm   -   10pm
•            10pm   - 6am.The call centre   managers are concerned   about the   current   quality   of   service,   measured   by   the   number of calls waiting to   be   handled. They are   therefore   considering   how   many   staff   are   required, and   how   best to   allocate them   between the   shifts.
The call centre   has   hourly counts of the   number   of   arrivals   for   2   weeks.   It   also   collected   the   time spent speaking to a   member of   staff   for   all   customers   in   this   period.   Using   this   data, answer the following questions.
(a)    Using a stationary approach,   estimate   the   average   number   of   servers   (per   shift)   that   are   required for this   system such that at   least 40%   of   calls   are   answered immediately, without   having to wait.
(b)    Using a total of 3 times   the   number   of   servers   identified   in   part   (a),   allocate   these across the three shifts   in away that controls   the   expected   number   of   calls   currently   ongoing and the   probability of   having to wait   in the   best way.
In   reality, the telephone   network at the centre can   only   handle   a   finite   number   of   calls   at   anyone   time.   If   the   network   is   full,a   new   call   will   be   declined. The   network   could   be   setup to   hold   15 calls,   25   calls, 50   or   100   calls. The cost   is   of each   configuration   is   approximately linear   in the   number of calls. The   managers will   need to   decide which   togo   for.
(c)      Explore   how the different call capacities   impact your   answers from   above.   For   each   case, when does the   probability of a   call   being   declined   reach   its   maximum,   and   what value does this take? What would your   recommendation   be   in   caller   capacity?   Provide a description of any   models   used   and   detail   any   assumptions that you   make.
Question   2   [20   marks]
A   local   removal firm offers two short term services,   a   self-drive   van-hire   in   which   the customer   hires the van   but   drives the van themselves, and a   full   removal   service   in   which   the firm also   provides a team to   move the customer’s   belongings.   All jobs   generally take   one   day. The company will only   accept   up to   5   customers   for   each   service   at   a   time.   If the   number of customers   on the   books for the following working   day   goes   above   5   for   either   service,   no   more work   is accepted on that   service.
The   income from the self-drive service   is £40, whilst   for the   full   removal   service,   the   income is £60.   However,   if the firm are   notable to complete   a job the   next   working   day, the customer   is offered a discount of   £15   or   £20   for   the   two   services,   respectively.   If   the customer still   hasn’t   been served, they are offered   a further   discount   of   equal   amount.
Currently, the firm   has 5 vans, three of which   are   set   up   to   be   insured   to   be   driven   by   hiring   customers   (and are   used exclusi代 写MSCI512: Simulation and Stochastic Modelling 2024/25 Coursework TaskPython
代做程序编程语言vely for this   purpose), and two   which   are   just   used   by   the company for the full   removal service.
The company   has   provided data showing the   number of   requests   made   in   each   day   and   the   number of customers on the   books   (at the   end   of   a   day   over   a   period   of the   last   6   months            (130 working days).
(a)    In the   long   run, what   is the   average   operating   profit   per   day   in this way? On   what proportion of the days are   not   all the vans   busy?   On   what   proportion   of   days   might   work   be turned away?
Suppose that the company could   hire   up to an   additional   2   vans   on   any   given   day. The   cost   of   hiring a van   is £50. These vans could   be   allocated   to   either   of the   services.
(b)   Considering a time   horizon   of 28 days,   determine a   policy   that   states   when   it   is   best   to   hire one van or two vans, and   to   which   services   should   they   be   allocated,   based on the   number of jobs currently   in the   books.
(c)      If this   policy were to start   5 days   after the   end   of the   data   period   you   have,   what   would the expected operating   profit   be?
(d)   Suppose there was a chance of   negotiating the   van   hire   cost.   Considering   a   range   of   values,   how would this change the   decisions and the expected   operating   profit?
Provide a description of any   models   used   and   detail   any   assumptions that   you   make.
Question   3   [45   marks]
A fast-food   restaurant   in   Lancaster   is currently going through   a   refurbishment and   is   looking   to   introduce two   new features when   it   reopens. The first   is that   it will offer   a   delivery   service, just open   between 4pm and 9pm.   It   will   also   only   be   available to   those   as   far   south   as Galgate, as far   north   as Slyne   and   Hest   Bank   and to the   west   into   Morecambe.   They   believe this will   help them to   attract   more customers and   so   increase   revenue,   complementing the   people who arrive at the   restaurant   in   person   (some of whomeat   in, whilst others take away). Their   projection,   based on   a   local   survey,   is that this   could   be   as   high   as an   increase of   10%.
The second   is that   it will   replace   its   current ordering   process with   some   large touchscreen   self-service   machines that send the order directly to the   kitchen.   They   hope   this   will   help them   reduce costs and   potentially   improve the time   it takes to   serve   a   customer.
This will also   mean that the   layout of the   restaurant will   have to   change.   Currently   there   are   30 tables   in the   restaurant.   However, for each automated system they   install,   they   will   need   to   lose   2 tables. Their experience   is that   people who sit   in the   restaurant to   eat   sometimes   come   back for an   additional order, such as   getting   a   dessert   or   a   coffee.   Whilst   they   want   the time   between the arrival and the   food   being   prepared to   be   small, they   don’twant   to   lose too   many tables and therefore   lose sales.
The current   procedure   is as follows. The customers arrive   and   order   their   food   (currently   by speaking to a   member of staff,   but this will   move to   the   self-service   machines   on   re-opening). After this, the food   is   prepared   by one of   6   members   of   staff.   Once the   food   is   prepared, the customers   can theneither take this food   away   and   eat   it   elsewhere   or   find   a         table and sit   in the   restaurant while they eat.   If   all   the   tables   are   taken,   customers   generally   take their food out. As   previously   mentioned, some   of the   customers   who eat   in   may   come      up to   reorder food and can theneither sit   in   (usually   this   second   period   of time   is   shorter   than the first)   or take   away.For food that   is   being delivered, the order   will   go   straight   to the   kitchen.   Once   the   food   is ready,   it will   be set   aside   ready for a courier   (employed   by the   restaurant)   to   deliver. They   are thinking that a sensible target would   be to   deliver   the   food   within   an   hour.
The   managers   need to decide:
1.         How   many couriers should they   employ?
2.       How   many self-service   order   machines   should   be   installed?   The   key   performance   measures to   bear   in   mind   are:
•         The   percentage of food orders which are   delivered within   1   hour   of the   order   being   submitted.
•         The time   it takes   between a customer arriving   and   receiving their   food.
•         The expected   number of orders completed   per   day.   The data   available   are
•         The   number of arrivals   per   hour to the   restaurant over   a two-week   period.
•          Manufacturer time trial data on   how   long   it takes to   use the   self-service   system.
•          For some customers   in one day,   the   following   information   was   tracked:
o   How   long   it took to   prepare food for an   order
o   How   long they stayed   in the   restaurant   (if they did), following the   order,
o   If they went for   a second order,   how   long   it was   before this food   was   ready   and   how   long they stayed   after that   (if they did)
•          For the time to deliver,   no   data   is yet available.   However,   the   restaurant   has   asked local couriers to   provide some data. They expect   that   collecting   the   order   and   going   back to a vehicle will take at   least five   minutes. Travel   times   for   the   area   identified are   likely to   be   less than   15   minutes, often around the   8-12   minutes   mark.
Produce a   report to advise the   restaurant owners   on   these   issues.   Consider   how   sensitive   the   results are to some of the   assumptions   made.   Include   details   of   any   models   developed.   [25   marks for conceptual and computational   model,   20   marks for   analysis].







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com

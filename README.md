# 留学生日常作业/课程设计/代码辅导/CS/DS/商科，仅为漂洋过海的你❥
标签：Computer Science、Data Science、Business Administration，留学生编程作业代写&&辅导

## 个人介绍:
本人是一名资深码农，酷爱投资。

为您提供 CS , DS , 商科 编程作业代写

<img src="design2023866.jpg"  width="200" />

Fundamentals of Actuarial Practice: Final Assessment 
Final Assessment Overview 
Scenario Background
Background: UBIC’s Roots
MegaCorp is an international conglomerate with subsidiaries spanning a wide array of industriesincluding 
transportation, energy, healthcare, electronics, and financial services. Its financial services business came 
into existence and grew through many acquisitions of insurance companies throughout the country of 
Baskadia. After many years and a management change, MegaCorp decided to focus its efforts on its core 
manufacturing competencies. Each non-core business was evaluated, and a decision was made to sell or 
spin them off through IPOs. M&A market analysis at the time concluded that a spin-off was the most 
lucrative avenue for the insurance business. Consequently, the United Baskadia Insurance Company 
(UBIC) was born through an IPO in 2010. 
Since UBIC’s legacy portfolio resulted from the acquisition of many individual financial service companies, 
the product portfolio is very diverse. It includes:
• Traditional life insurance
• Universal life insurance
• Annuities
• Long term care insurance
• Automotive insurance
• Homeowner’s insurance
UBIC continued operations maintaining the legacy block and selling new business for several more years
after the IPO. Taking a cue from its parent company’s heritage, the life and general insurance segments 
are operated as semi-autonomous business units so that each can maintain more focus and develop their 
core competencies.
In recent years, adverse experience and assumption updates have forced UBIC’s life business to post 
additional reserves and capital. UBIC felt extreme capital constraints of issuing new business, suspended 
new sales, and ultimately solicited acquisition opportunities for its life insurance business. Consequently, 
UBIC’s life insurance business was sold to Gold Standard, a Cascadian financial services company. Gold 
Standard acquired UBIC’s lines of traditional life insurance, universal life insurance, and annuities. Gold 
Standard already had a profitable life insurance business line and the UBIC acquisition allowed them to 
further leverage their existing capabilities and achieve geographic diversification benefits. Postacquisition, UBIC operates mostly autonomously, but with strategic guidance from the new owner, Gold 
Standard.
The Need for Long Term Care Insurance in Cascadia
Several years have passed since Gold Standard acquired UBIC’s life insurance business. Given Cascadia’s 
demographic landscape of an aging population and UBIC’s pedigree dealing in long term care (LTC)
insurance, the company is eager to explore launching a new LTC insurance product in Cascadia. Gold 
Standard believes it can jump start its LTC insurance endeavor by first acquiring UBIC’s legacy block of 
business which was sold in Baskadia.
A large portion of Cascadia’s population is comprised of those aged 65 and older. Mortality improvement 
trends have been significant in Cascadia, resulting in people generally living longer. Furthermore, younger 
generations have been compelled to deprioritize having large families, or families at all for a variety of 
reasons. This population dynamic causes a problem where there will be a severe shortfall in the number 
of younger people available to care for this fast-growing older segment of the population. This is very 
relevant to Cascadia, where the population under age 65 is expected to increase by only 15% by 2050 
while the segment over age 65 is expected to grow almost 200% in the same time frame. Elderly care costs 
have also increased from inflation and higher labor costs for health aides, therapists, and nurses. There 
are currently no LTC insurance offerings in Cascadia, so these costs are typically paid out-of-pocket as they 
are generally not covered by health insurance. Gold Standard believes this is where LTC insurance could 
provide value to policyholders.
Long Term Care Insurance Background
LTC insurance is used to cover the costs of care for people who cannot perform at least two of the six 
activities of daily living (ADL): bathing, eating, dressing, continence, toileting, and transferring. The costs 
covered could be used for nursing homes, assisted living facilities, home health aides/nurses, etc. Many 
LTC policyholders on claim have typically been diagnosed with a chronic illness or disability. With 
policyholders having these sorts of diagnoses, it is often unknown when they will come off claim, if ever, 
adding a potential longevity risk to Cascadia.
A LTC policyholder will pay premiums to the insurer, and in return will receive benefits for covered LTC
costs if they meet the ADL eligibility. Their benefit could be in the form of a specified dollar amount per 
day or direct reimbursement for covered long-term care costs.
This would be the first LTC product being sold in Cascadia, so there is little regulatory guidance around 
this new market. Consequently, the new LTC product under consideration would use a simple design 
where morbidity benefits are paid as a flat amount per unit of face amount of the policy. Gold Standard 
is specifically interested to acquire UBIC’s legacy portfolio of this basic product design as an introduction 
to LTC insurance.
Your Role
You work as an actuarial student in the section of UBIC acquired by Gold Standard. You will support the 
assessment of the Cascadian market for the potential LTC product and resolve various challenges
acquiring the legacy LTC insurance block and bringing a new product to market. All your analysis should
follow the actuarial standards which all actuaries abide to.
Deliverables Guidance
Throughout this assessment, most of your memos are internal and typically directed to your actuarial 
manager. These are less formal memos for an audience you work with often. You may assume a higher 
level of familiarity from this audience and may not need to go through every technical detail. 
One management memo is directed to Gold Standard’s Board of Directors. The tone and formality of this 
memo should accommodate the needs of a less technical audience that you do not work with often. This
memo should be written with a focus on structure, format, and appropriate content. Be sure to use 
language that is clear and concise when communicating with the board.
Overall Length of Document
While there is no strict requirement regarding the number of pages, approximately 15-20 pages (excluding 
appendices) are often appropriate to fully, yet succinctly, address the questions. Recall, the purpose of 
the assessment is to measure your ability to work on actuarial problems in a practical exercise. You should 
effectively and efficiently convey the information that answers each task / question.
 
• Best Estimate Liability (BEL): The present value of future liability cash flows using best estimate 
TASK 1 – Valuation Exercise
You have been assigned to perform the initial valuation of the legacy LTC block being acquired. Cascadian
Generally Accepted Accounting Principles, or CGAAP, for life insurance applies the Building Block
Approach, or BBA. Note that the initial valuation will apply several simplifications which will provide UBIC
and Gold Standard an early read on the required reserve levels even though the acquisition has not yet
been executed. This analysis will play a critical role in planning and forecasting activities for the broader
company. Given these simplifications, you should assume that all the necessary reserving guidance is
presented in the description below, and no outside knowledge is required.
CGAAP Description:
The Building Block Approach (BBA) is used to value liabilities under CGAAP. The total liability is the sum
of several “building blocks”, as described below:
assumptions.
• Risk Margin: Perform the same calculation of the present value of future liability cash flows but 
use assumptions with explicit PADs (Provisions for Adverse Deviation). The excess of this present 
value using PAD assumptions over the BEL is the Risk Margin.
The best estimate discount rate used for calculating the BEL is the risk-free rate, defined as the 750-day
moving average government bond yield plus a spread, which can be no more than 150 bps.
In the current scenario, the BBA is determined on a legacy block of business during an acquisition. 
Consequently, the sum of the BEL and Risk Margin is compared against the fair value of the liabilities (FVL), 
which represents the price that would be received to sell an asset or paid to transfer a liability in an orderly 
transition between market participants. Two situations can result from this comparison:
1. FVL > (BEL + Risk Margin)  Residual Margin
a. If the FVL exceeds the sum of the BEL + Risk Margin, the excess is called the Residual 
Margin and the company will establish a liability.
2. FVL < (BEL + Risk Margin)  VOBA
a. If the BEL + Risk Margin exceeds the FVL, the excess is called the Value of Business 
Acquired (VOBA) and the company will establish an asset.
These scenarios are illustrated below:
Questions:
Using the CGAAP description above and the data from the ‘FA_4Q23_UBIC_2.0_Model.xlsm’ Excel 
workbook, perform the calculations below and communicate your results in an informal memo to your 
project lead. Your memo must include a clear, graphical representation of the BBA liability to help convey 
your results.
a) Briefly explain the concept of time value of money, which is a critical factor in the CGAAP reserve 
calculation. Your explanation should cite the specific example found in the workbook for the
present value of 1M Cascadian dollars paid in December 2040.
b) Calculate the CGAAP Best Estimate Liability for the legacy LTC insurance block. 268.5M
c) Calculate the CGAAP Risk Margin for the legacy LTC insurance block. The team has determined
that the Risk Margin PADs shall be 5% on each assumption and a 50bps shift on the discount
vector. 382.2 Million
d) An investment bank contracted by Gold Standard to appraise UBIC’s legacy LTC insurance block 
has determined a fair value of 400M Cascadian dollars. Using their approximate fair value,
calculate the VOBA or Residual Margin. 250.7Million
Note: In order for the excel workbook to function properly for this task, you will need to have macros
enabled.
Create your memo in the appropriate section of the Microsoft Word template. Remember, you must
include a clear, graphical representation of the BBA liability.
TASK 2 – Sensitivity Analysis 
Long term care insurance is a new product to Gold Standard and the Cascadian market. Consequently,
Gold Standard’s senior leadership team is interested to see a sensitivity analysis of UBIC’s legacy LTC
insurance block. This sensitivity analysis will also provide vital information to understand the critical
drivers of profitability for LTC insurance for future Cascadian product endeavors. You will perform the
sensitivity analysis on the legacy LTC insurance block using the ‘FA_4Q23_UBIC_2.0_Model.xlsm’.
a) Perform a sensitivity analysis on the projection model assumptions. Summarize the results.
b) Which assumption is the most sensitive? Justify your response.
c) Which assumption is the least sensitive? Justify your response.
d) Are any of the projection model assumptions interdependent?
e) Are there any projection assumptions that should be added to the model?
You should present your findings and analysis in the form of an outline to be converted into a
PowerPoint presentation. Your project lead has asked you to summarize your findings into an outline
that will be turned into a PowerPoint slide deck of between six and ten slides of content.
To do this task, create a main outline bullet signaling the title of a slide and sub-bullets below the main
outline bullet to outline the content of a slide. If needed, insert a table or chart as a sub-bullet. Do not
use more than six sub-bullets below each main bullet; slides need to be concise, with appropriate
content, and not overly crowded.
Be conscious that your outline will be used to create PowerPoint Slides for your project lead. Do not
put too much or too little content below each title bullet. For example, if you put a table below a title
bullet, do not also have five additional sub-bullets, because that would not fit on a PowerPoint Slide.
Place your outline in the appropriate section of the Microsoft Word template.
 
• Benefit Increase Option:
o
TASK 3 – Morbidity Experience Study & Product Enhancements
After reviewing your sensitivity analysis and given that LTC insurance is a new product for Gold Standard
and the Cascadian market, actuarial leadership has requested additional analysis. They have heard
industry talk about LTC insurance carriers missing assumptions and therefore needing to increase
reserves. Consequently, they are interested to see how experience on UBIC’s legacy LTC block has
emerged.
Furthermore, your actuarial colleagues from the pricing department would like to evaluate if additional
product features could reduce reserve volatility while also making the product more attractive to potential
policyholders. They have asked you to evaluate several potential product enhancementsto the basic term
LTC insurance product from UBIC’s legacy block. The pricing team provided the following product features
for consideration:
Morbidity benefit rate increases by a percentage each year the policy remains inforce.
• Life / LTC Insurance Combination Product:
o Rather than a standalone LTC insurance product, a LTC rider would be added to a basic 
traditional life insurance product. If a policyholder went on morbidity claim, the face 
amount could be drawn down to pay morbidity claim costs.
• Return of Premium Rider:
o Rider on LTC insurance product which would return all premium paid to the policyholder 
upon death.
Please complete the following tasks:
a) Using the ‘FA_4Q23_UBIC_2.0_Task5.xlsx’ workbook, perform an annualized experience study on 
the morbidity experience over the last 5 years on UBIC’s legacy LTC insurance block. Draw and 
present conclusions about each of the 5 cohorts and recommend any assumption adjustments.
b) Evaluate the pros and cons of each of the proposed product features. Should each feature be 
incorporated into the new LTC insurance product for Cascadia?
Note: The Excel workbook used in Task 5 should be considered independently of that used in Task 2 & 3.
Create a memo to your supervisor for these tasks in the appropriate section of the Microsoft Word 
template.

## 作业代写价格:

|类型|美元|人民币|
|-----:|-----:|-----:|
|Assignment|$60-$120|¥400-¥800|

### 为了方便快速定价和确定是否代做，麻烦提供私聊的时候提供以下信息：
如果是作业，提供本次作业要求文档；如果是考试，提供考试范围和考试时间
一两句话概括一下作业任务或者考试任务，比如”可以帮忙实现一个决策树算法吗？”、”网络安全选择题考试，范围是内网横向移动知识点”
### 作业定价有两种方式：
    - 根据定价标准进行
    - 通过微信我们一起协商
## 联系方式

微信（WeChat）：design2023866

<img src="design2023866.jpg"  width="200" />

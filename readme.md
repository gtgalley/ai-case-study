Nvidia and AI

## Overview and Origin

* Nvidia Corporation

* When was the company incorporated?
    - April 5th, 1993

* Who are the founders of the company?
    - Jensen Huang, Chris Malachowsky, and Curtis Priem

* How did the idea for the company (or project) come about?
    - At the time of the founding of the company, Malachowsky and Priem were both working for Sun Microsystems while Huang was the director of CoreWare at LSI Logic. They met at a Denny's roadside diner in East San Jose, where an agreement was reached on terms by which to start the company. Malachowsky and Priem were frustrated with Sun Microsystem's management at that time and were more keen on conceiving their own project, whereas Huang's position running a division at LSI left him more reluctant to take the risk. However, the grand vision discussed between the three of them compelled Huang to leave his position and take up the role of CEO of the new startup. With only $40,000 in the bank, the company was born with the intention to take advantage of the nascent gaming industry and the necessity for accelerated computing to power this new obsession with computer graphics. 

* How is the company funded? How much funding have they received?
    - The early years of Nvidia as a company and as a business were rocky, and success was far from a guarantee. Huang has since admitted that a particular $5 million investment from Sega's president in 1996 single-handedly kept the company afloat for another six months time, as they were otherwise functionally bankrupt. This financial hardship gave rise to their first unoffical motto:
        >Our company is thirty days from going out of business
    - Following this investment, and down to about 40 employees in 1997, Nvidia successfully sold about a million of their primitive RIVA graphics accelerator products to keep the company afloat and solidify Nvidia's reputation as a trusted and capable manufacturer. Since then, the majority of Nvidia's funding has come from the sale of products, with their yearly revenue now eclipsing $60 billion. 
    - Nvidia held its IPO in January 22nd, 1999 at $12/share. In recent years, due to eruptions in share price, Nvidia's market cap has surpassed 3.5 trillion, reflecting widespread optimism regarding their position as the most successful and influential graphics processing unit developer in the world. 

## Business Activities

* What specific problem is the company or project trying to solve?
    - In this case study, I wanted to look closer at what Nvidia is doing to integrate AI specifically into the gaming capability of their graphics cards. DLSS, or deep learning super sampling, AI is used to, in its simplest form, create additional frames that do not need to be individually rendered by the GPU, and improve image quality, typically referred to as "AI upscaling". This technology allows users of capable graphics cards to enjoy experiences that would otherwise require either significantly more powerful graphics cards, or a reduction in workload - such as resolution, FPS, lighting quality, particles, etc. 

* Who is the company's intended customer? Is there any information about the market size of this set of customers?
    - Nvidia's customer base is by no means lacking a solid foundation, and they are every bit as interested in maintaining current customers as they are attracting new ones. On the corporate level, four single customers account for approximately 40% of Nvidia's revenue, including: Microsoft (15%), META (13%), Amazon (6.2%), and Alphabet (5.8%). Their market share continues to grow -they currently control about 80% of the AI GPU market- and at this point are selling approximately 4 million GPUs per year. They also sell GPUs at a consumer level, to individuals looking to power their own hobbies or recreations. The exact figures for desktop GPUs sold are difficult to pin down due to conflation wth prebuilt PCs and laptop GPUs, but Nvidia does control about 88% of the desktop GPU market. 

* What solution does this company offer that their competitors do not or cannot offer? (What is the unfair advantage they utilize?)
    - The proprietary algorithms that have been developed and are now featured in the released versions of DLSS Frame Generation, DLAA (deep learning anti-aliasing), and DLSS Ray Reconstruction are far beyond the capabilites of other GPU companies at this point. The only significant competitor to Nvidia in the desktop GPU space is AMD -with Intel beginning to emerge as a minor contender- but AMD's only competition to DLSS-style technology is FSR, or FidelityFX Super Resolution, and it was released approximately three years later than Nvidia's own DLSS and generally runs about a generation behind in terms of overall effectiveness. In a demo performed with modern hardware on modern games, DLSS contributed to frame boosts anywhere from 200% to 550%, a level of improvement which offers the user a great deal of freedom to enjoy otherwise implausible settings. 

* Which technologies are they currently using, and how are they implementing them? (This may take a little bit of sleuthing-you may want to search the company’s engineering blog or use sites like Stackshare to find this information.)
    - To put it simply, DLSS features machine learning in which an AI model is tasked with analyzing in-game frames and, using the data it gathers, contructs new frames. These frames are either at a higher resolution, with the detail being added in places deemed appropriate by the samples on which the AI was trained, or added to the existing frames to give the effect of a higher frame rate without the respective GPU stress. In recent implementations, boosts in performance have skyrocketed from around 70% to an impression 200-400%. In addition to frame quality and quantity, the content of each frame has also been given room for more granular adjustment with a technology called DLAA, or deep learning anti-aliasing. Normal anti-aliasing relies on real-time calculations to perform brute-force sweeps that smooth and cull, passing over images to present either more or less smooth final products usually at the expense of motion clarity and edge definition (with a few exceptions depending on the specific AA technology in use). Here, Nvidia has trained machine learning algorithms to recognize edges more accurately and improve sharpening without sacrificing performance, as well as ray reconstruction, a technique to improve the fidelity of ray tracing -a form of graphically intensive and accurate light rendering- which replaces pixels between ray-traced samples with AI-trained images. 

## Landscape

* What field is the company in?
    - Nvidia Corporation is the largest and most powerful producer of Graphics Processing Units and AI hardware, and currently trading places for the most valuable company in the entire world with Apple. 

* What have been the major trends and innovations of this field over the last 5-10 years?
    - The Renaissance of AI in the last 5 or so years has rocketed Nvidia to the forefront of every single major (and minor) company's board meetings and R&D discussions, and it is no mystery as to why Nvidia's data center GPU's are constantly at risk of backorder as they operate at maximum capacity around the clock. Any company that wishes to innovate in their own way on the recent developments of AI requires hardware to do so, and therefore must go through Nvidia unless they are willing to try their hand at a smaller manufacturer or in-house technology. However, given Nvidia's massive R&D budget and long-time dominance in the field, the risk/reward balance does not favor innovation against this tech giant. As such, recent trends have rendered Nvidia a household name, with businesses around the world clamoring to get their hands on as many data center GPUs as possible to facilitate the adoption of new emerging AI technologies. 

* What are the other major companies in this field?
    - Intel and AMD are the only notable competitors in this field, but the market share currently tilts heavily in favor of Nvidia. In 2023, Nvidia held an 87% share, with AMD at 10% and Intel at 3%. It is healthy for a field to have competition, so my hope is that these competitors continue to see sufficient sales and offer alternatives in an attempt to keep prices competitive and R&D flowing. Intel and AMD certainly have large enough niches of their own in the tech world that they are not at risk of being stamped out anytime soon, but competing in the discrete GPU sector with Nvidia is an unenviable task. 
    - Other major companies in this field include individual companies that are in the process of developing their own AI solutions so as to avoid relying on Nvidia's hardware. They are myriad and the successes they enjoy vary widely, but it goes without saying that the expense of developing an in-house product, once it is finalized, is far less than the expense of constant brand-new data center GPUs from Nvidia. 

## Results

* What has been the business impact of this company so far?
    - It is difficult to understate the impact that Nvidia has had on the tech world in the past several decades. The current state of the world would undoubtedly be different if that initial risk had not been taken back in 1993, and since then, nearly every notable achievement involving the term "AI" has in some way or another involved Nvidia. They have been developing their own proprietary technologies to accompany their hardware, to be sure, but I think the greatest of their achievements to date is for their company's legacy to be immutably associated with this unprecedented technological boom. 

* What are some of the core metrics that companies in this field use to measure success? How is your company performing based on these metrics?
    - Investors in tech companies like Nvidia are constantly looking to see more and more sales, with cash flow being the number one indicator of both current success and future boons. As mentioned above, Nvidia's revenue has recently exceeded $60 billion and is currently listed at close to $100 billion, a figure that ranks them at 77th among all countries worldwide. Compared to similar tech companies, they are far and away the most successful, with one of their most significant struggles as a company of late being that many senior developers have been retiring as a result of the recent stock price hike, rendering their stock bonuses highly valuable. If current trends continue, and all signs point to this being the case, then Nvidia should continue capitalizing on this AI fever for some time; this is a big reason why their stock price sentiment is so positive, which is another key metric for success.  


## Recommendations

* If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!)
    - Though they seem to be doing just fine in the areas they are currently engaged in, for a company as large as Nvidia with the resources they have at their disposal, I would like to see some forays into more public applications of their own technologies. As a musician currently studying to get my master's degree in viola performance, I think that there is room for Nvidia to partner with software companies, or create their own solutions, allowing consumers to take advantage of hardware in a non-gaming atmosphere at a local level. Solutions like Microsoft's Cortana and the like are widely disliked, whereas OpenAI's ChatGPT and similar LLMs are all server-based and do not run locally. Though there are undoubtedly countless hoops to jump through that may render ideas like this unfeasible, integrating AI into a system in the form of a multifunctional assistant that is also imbued with functional computing power and intelligence may open the door for improved ease of use and more readily explorable functionality. 

* Why do you think that offering this product or service would benefit the company?
    - The easiest way I could see this product benefitting the company is in the attraction of new customers. The excitement of more integration of AI into our workstations from a trusted company such as Nvidia, while undoubtedly garnering some backlash, would likely overall receive support in the most important form: additional sales. 

* What technologies would this additional product or service utilize?
    - A technology like this would be able to access the computing power of Nvidia's discrete GPUs at the behest of the user in a similar way to the upcoming enhanced functionality of Apple's Siri in iOS 18.1. Confusing or difficult tasks, the solutions for which would otherwise be googled, could be much more easily fetched for individuals and their unique machines through these smart terminals that have access to the details of the machine on which they run. The longer this product would exist for users worldwide, the more effective it would become, seeing as this is a new use case for an assistant-style chat bot with additional functionality that would need data from which to pull in order to streamline responses and give actual helpful information in edge cases. Opportunity for feedback would be paramount in supporting users through instances in which the technology does not work as intended, but hopefully in time the bugs present less and less frequently and pale in comparison to the impressive functionality of the properly operating product, which would likely be opt-in. 

* Why are these technologies appropriate for your solution?
    - I suppose we will see based on the success of Apple's iteration of such technologies whether or not this sort of behavior is well-accepted by the general population on a smartphone, much less on a PC. A tremendous amount of research and test running would need to be undergone before a project such as this would be ready for proliferation, as a serious mistake in this field with as wide of a reach as Nvidia has could spell disaster to the tune of billions, or even trillions, of dollars. However, we as humans are not averse to efficiency, and before long, whether we like it or not, are often forced to adopt new solutions that enhance or assist our ability to do tasks. The technologies applicable for this project, including but not limited to the application of LLMs, machine learning, and generative models, are currently accepted as the most appropriate solutions for achieving the desired results in similar contexts. 

## Sources

- https://en.wikipedia.org/wiki/Nvidia
- https://www.nvidia.com/en-us/geforce/technologies/dlss/
- https://finance.yahoo.com/news/single-customer-made-19-nvidias-143533924.html?guccounter=1&guce_referrer=aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbS8&guce_referrer_sig=AQAAAESPq-Ix-xk--f621Bn-nxHOOMDcCqZ_cwUaD3Okfpr9phLfpI6JST4zI9QPi-hgXZJE1uxhXvtbbOA2hrCfiJyegb4btaFONJIt221W3Ch3-YJmZZKhGaZiPE_zjFwuYehfXsSZMh3rvzN4F7slV0DHCTwlAMizBxLAcR1yafLB
- https://www.tomshardware.com/video-games/pc-gaming/steam-survey-suggests-more-people-bought-the-rtx-4090-than-the-steam-deck-along-with-millions-of-other-rtx-40-series-gpus
- https://www.corsair.com/us/en/explorer/gamer/gaming-pcs/dlss-vs-fsr-which-is-better/#:~:text=In%20general%2C%20DLSS%20is%20ahead,games%20playable%20for%20more%20people.
- https://wccftech.com/gpu-market-rebounds-q2-2023-amd-nvidia-intel-increased-shipments-discrete-gpus-up/
- https://companiesmarketcap.com/top-companies-by-market-cap-gain/

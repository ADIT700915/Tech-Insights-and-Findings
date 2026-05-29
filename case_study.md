**CASE STUDY ON LIVE LINKEDIN PROFILE FETCHING VIA URL** :

Incidence:  

I gave a prompt to three AI models:
1) Google Gemini  
2) OpenAI ChatGPT
3) xAI Grok     
Rate this LinkedIn profile on scale of 0 to 100 [profile link]  

Results:  

Only Grok was able to retrieve and rate the profile through the provided link .ChatGPT produced non- deterministic results i.e. only highly visible or active profiles could be reliably retrieved and rated. Google Gemini could not fetch profile data through the link. 

Reasons Found:  

1) LinkedIn's Protective Infrastructure:  
    LinkedIn actively restricts automated extraction of profile data because profiles contain personal information, employment history, networking data and other sensitive details. It uses antibot systems that distinguish humans and automated softwares by analyzing behavior and using mechanisms such as CAPTCHA challenges .These systems block web scrapers, automated tools ,including AI agents, from accessing user profiles .Since, such agents generally do not possess valid login credentials ,they can't read the content.

2)  Why Did Gemini Fail to Retrieve Profile Information?  
   Gemini primarily relies on indexed and cached web content rather than functioning as a full real time browser in every situation. {it basically  stores organised copies of webpages so as to retrieve info without visiting the original site every time}.As a result, the browsing behavior is selective and constrained by restrictions.Such models prioritize privacy safeguards .
3) Why Did ChatGPT Show Varying Results?  
   Profiles with stronger publicly discoverable signals- such as larger number of connections,visible technical posts,higher activity levels and fewer matching profiles  return more visible data in system's internal search index allowing it to generate ratings.
   
   However,when limited profile metadatais available externally ,the AI may be unable to access sufficient information about the profile .Such models rely on realibility threshold {answering only when trustworthy information is available } and avoid hallucinating details.They prioritize safety ,accuracy and compliance over forceful access.
   
3) Why Did Grok Succeed?
   Grok is integrated with X (Twitter) which shares data with LinkedIn.It uses more aggressive live web retrieval{searching the internet in real time}.It may also operate with a less conservative response policy {it offers answer even if not much sure} In the meanwhile, Grok's success may not be consistent across all profiles, all times, or all LinkedIn privacy settings. The case study represents a single successful retrieval under specific conditions.


      
Recommendations:

Use Grok when you want AI to read LinkedIn URL directly.Use ChatGPT,Gemini or any other AI systems when you are willing to provide content such as..... for deeper analysis and more  refined strategic feedback.

The case study illustrates that the differences in results across AI systems can arise from variations in live web retrieval capabilities , tolerance for partial information and platform access -control measures.


   
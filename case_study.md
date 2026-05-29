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
   Gemini primarily relies on indexed and cached web content rather than functioning as a full real time browser in every situation. {it basically  stores organised copies of webpages so as to retrieve info without visiting the original site every time}.As a result, the browsing behavior is selective and constrained by restrictions.Such models prioritise privacy safeguards.
3) Why did ChatGPT show varying results?  
   Profiles which have more publicly discoverable signals such as more connections,visible technical posts,active posting/activity ,fewer matching profiles etc return more visible data in system's internal search index allowing it to generate ratings, while if there is  limited profile metadata available externally then AI can't access the profile .Such models rely on realibility threshold{answering only when have trustworthy information } and avoid hallucinating details.It chooses safety and compliance over forceful access.
   
3) Why Grok succeeded?  
   Grok is integrated with X (Twitter) which shares data with LinkedIn.It uses more aggressive live web retrieval{searching the internet in real time}.Grok also has less conservative response policy {it offers answer even if not much sure} In the meanwhile, Grok's success may not be consistent across all profiles, all times, or all LinkedIn privacy settings. The case study represents a single successful retrieval under specific conditions.


      
Recommendations:

Use Grok when you want AI to read LinkedIn URL directly.Use any other AI when you are willing to go with paste and analyse method to have deep strategic refined feedback.The case study illustrates that the difference in results from different AI systems arise due to different live web retrieval capabilities , different tolerance for partial information and platform's access -control measures.


   
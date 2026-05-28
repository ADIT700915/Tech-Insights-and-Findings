#**CASE STUDY ON LIVE LINKEDIN PROFILE FETCHING VIA URL**   

Task Prompt:  
Rate this linkedin profile on scale of 0 to 100 [profile link]  

Tools Tested:  
1) Google Gemini  
2) OpenAI ChatGPT
3) xAI Grok     

Results:  

Only Grok was able to access and rate the profile via while other 2 failed to access the profile and asked for images or screenshots to be uploaded for scaling.  

Reasons:  

1) Why GEMINI failed?  
   Gemini relies on cached indexing mechanism and its not a true real time browser. {it is basically the process of storing organised copies of webpages so as to retrieve info without visiting the original site every time}.The browsing behavior is selective and constrained by restrictions.  
2) Why GPT failed?  
   ChatGPT when attempted to access the profile link was restricted by bot detection systems{ technology to block automated tools} and robot.txt restrictions.{linkedin restricts automated crawling paths}.  
3) Why Grok succeeded?  
   Grok is integrated with X (Twitter) which shares data with linkedin.It uses more aggressive live web retrieval{searching the internet in real time}.Grok also has less conservative response policy {it offers answer even if not much sure} In the meanwhile, Grok's success may not be consistent across all profiles, all times, or all LinkedIn privacy settings. The case study represents a single successful retrieval under specific conditions.

Observations and Findings:  

Specifically talking, LinkedIn uses anti-scraping infrastructure {restricts unauthorized AI systems to access profile}to protect valuable data such as
professional identities, employment history etc .Since ChatGPT and Gemini are more concerned about transparency , they are more conservative around login-gated pages .The 2 systems have high realibility threshold{ answering only when confident} than Grok which sometimes hallucinates confidence and presents incomplete data.
      
Recommendations:

Use Grok when you want AI to read LinkedIn URL directly.Use any other AI when you are willing to go with paste and analyse method to have deep strategic refined feedback.The case study illustrates that the difference in results from different AI systems arise due to different live web retreival capabilities , different tolerance for partial information and platform's access -control measures.


   
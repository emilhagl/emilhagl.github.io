---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
---

<!-- <div style="display: flex; align-items: center; gap: 20px;"> -->
<!-- <div style="display: flex; align-items: center; gap: 20px; flex-direction: row-reverse;">
  <!-- Image with circular style and max-width -->
  <!-- <img style="border-radius: 10%; max-width: 250px;" src="{{ '/assets/images/profile_light.png' | relative_url }}" alt="Profile Image"> -->
  <!-- Text and Title next to the image -->
  <!-- <div>
    <h2>A little bit about me.</h2>
    <p>I am a PhD Student from Umeå. I am a PhD Student from Umeå. I am a PhD Student from Umeå. I am a PhD Student from Umeå.  </p>
  </div>
</div> -->

<!-- <div>
    <p>This website provides a summary of my research and links to the articles in my PhD thesis.</p>
</div> -->

<div style="
  display: flex;
  align-items: center;
  gap: 20px;
  flex-direction: row-reverse;
  flex-wrap: wrap;">
  <!-- Image with circular style and max-width -->
  <img style="border-radius: 10%; max-width: 250px; flex: 1; min-width: 150px; margin: 0 auto;"
       src="{{ '/assets/images/profile_light.png' | relative_url }}"
       alt="Profile Image">
  <!-- Text and Title below the image -->
  <div style="flex: 2; min-width: 200px; text-align: left;">
    <h2><strong>A little about me and my research</strong></h2>
    <p> I am a PhD Student in Computer Science at Umeå University in Sweden. My research concerns the application of AI to marketing. Specifically, I study the use of webpage content, rather than personal data, for ad targeting—a strategy known as contextual advertising. My thesis includes  for understanding online content using Natural Language Processing (NLP) and the impact of online contexts on advertising effectiveness.
     <br><br>
    <!-- My thesis includes articles on which explores (i) how natural language processing (NLP) can be leveraged to analyze online content, (ii) examines the impact of online contexts on advertising effectiveness and (iii) the implications on consumers and advertisers of contextual versus personal advertising. <br><br> -->

    Before my PhD, I earned a B.Sc. in Industrial Engineering and Management and an M.Sc. in Computer Science and Machine Learning from KTH Royal Institute of Technology in Stockholm. <br><br>

    This website provides a summary of my research and links to the articles that constitute my PhD thesis.    
     </p>
  </div>
</div>



<!-- <div style="display: flex; align-items: center; gap: 20px;"> -->
<!-- <div style="display: flex; align-items: center; gap: 20px; flex-direction: row-reverse;">
  <div>
    <h2>AI-Driven Contextual Advertising</h2>
    <p>I am a PhD Student from Umeå. I am a PhD Student from Umeå. I am a PhD Student from Umeå. I am a PhD Student from Umeå.  </p>
  </div>
</div> -->



## **Project Overview**

My research on contextual advertising is motivated by two key factors. First, initiatives by tech giants, legislation such as GDPR, and societal concern about consumer privacy and fairness are limiting the use of personal data for ad targeting, making contextual advertising a compelling alternative. Second, the abundance of analyzable online media and the advanced capabilities of modern AI has opened new possibilities for contextual advertising.

My thesis, which consists of six articles spanning natural language processing, controlled experiments with online participants, and conceptual analyses, provides insights into:

- **(i) Techniques for understanding and grouping the topics and sentiments of online content**, with multiple marketing applications, including ad targeting.  
- **(ii) The impact of media contexts on ad perceptions and consumer behaviours**, highlighting how different online contexts influence the effectiveness of advertisements.    
- **(iii) The consumer and social implications of AI-driven ad targeting**, the consequences when AI decides who messages are targeted to based on contextual and personal data.
- **(iv) Advice for marketers in selecting ad targeting strategies** , focusing on the use of AI, personal and contextual data, under the consideration of data availability, advertising objectives, regulations, and ethical aspects.

## **Article Categorization and Research Objectives**

The six articles in my thesis can be grouped into three research domains. Below is an overview of the focus of each domain, along with the respective research objectives of each article.

1. **Natural Language Processing for Analyzing Opinionated Content** (Articles 1 & 2) <br>
  - Techniques for analysing and structuring the topics and sentiments within online content, where ad targeting is one application. Specifically, I use LLMs to extract fully contextualized aspect-sentiment pairs, termed *opinion units*, from online reviews (Article 1 & 2).  
  - I demonstrate the performance of opinion units as a chunking strategy in opinion search (Article 1) and topic modeling (Article 2). Topic modeling of opinion units generated from product reviews, offers a comprehensive understanding of customer discussions, capturing both the topics they are focused on and the strength of their sentiments. By correlating these topics with business metrics such as star ratings, valuable insights can be uncovered regarding how specific concerns influence business outcomes (Article 2).
  <!-- The use of opinion units overcomes challenges found in previous work, particularly those related to separating individual opinions within reviews and enhancing the interpretability of which sections of the raw text influenced the clustering or regression result. -->
  <br><br>

2. **Controlled experiments with online participants** (Articles 3 & 4) <br>
   - How does the online media context influence the effectiveness of ads? (Article 3 & 4)
   - How do the underlying mechanisms of contextualized and personalized advertising influence consumption intentions and the memorability of ads (Article 3)?
   - Should advertisers avoid advertising alongside negative contexts? (Article 4)
   <br><br>  

3. **Conceptual and Technical Commentary** (Articles 5 & 6) <br>
   - How can AI from a technical perspective be applied within contextual advertising? We review relevant work and provide technical insights around effective and non-privacy infringing ad targeting. (Article 5)  
   - What are the consumer and social implications of AI-driven advertising? We examine aspects such as AI-transparency, self-optimization, and the balance between using personal and contextual data for targeting. (Article 5 & 6)  
   - How can marketers determine the optimal level of AI automation and the balance between personal and contextual data for their ad campaign? Considerations include data availability, advertising objectives, regulatory compliance, and ethical considerations. (Article 6)

<!--
# Articles listed
Link to an article.
[Download the Opinion Units PDF]({{ '/assets/articles/opinion_unit.pdf' | relative_url }}) -->

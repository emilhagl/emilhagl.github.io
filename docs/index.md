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
- **(iii) The consumer and social implications of AI-driven marketing**, the consequences when AI decides who messages are targeted to based on contextual and personal data.
- **(iv) Advice for marketers in selecting ad targeting strategies** , focusing on the use of AI, personal and contextual data, and the consideration of data availability, advertising objectives, regulations, and ethical implications.

## **Article categorization & research questions**

The articles in my thesis fall into 3 main categories.

1. **Natural Language Processing (NLP) work** (Articles 1 & 2) <br>
  - NLP-techniques/systems for understanding the topics and sentiments of online content, where ad targeting is one application. Specifically: I use LLMs to extract fully contextualized aspect-sentiment pairs, dubbed \emph{opinion unbits} in online reviews (Article 1 & 2).  
  - Demonstrate the performance of opinion units as a chunking strategy in opinion search (article 1) and topic modelling (Article 2). Topic modelling of opinions can provide picture of consumers' opinions and regression of topics unto business metrics and outcomes  (Article 2).

2. **Controlled experiments with online participants** (Articles 3 & 4) <br>
   - How does the surrounding media context influence how online ads are perceived (Article 3 & 4)?
   - Should advertisers avoid advertising alongside negative contexts? (Article 4)

3. **Conceptual and technical commentary articles** (Articles 5 & 6) <br>
   - How can/should AI from a technical perspective be applied within online advertising targeting? Examining methodologies, applications for effective and non-privacy infringing advertising (Article 5)  
   - What consequences does AI have on consumers, and societal implications? (Article 5)  
   - How should marketers choose advertising strategies with regards to AI, data, regulations... (Article 6)

<!--
# Articles listed
Link to an article.
[Download the Opinion Units PDF]({{ '/assets/articles/opinion_unit.pdf' | relative_url }}) -->

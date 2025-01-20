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
    <h2><strong>A little about me and my research.</strong></h2>
    <p> I am a PhD Student in Computer Science at Umeå University in Sweden. My research concerns the application of AI to marketing. Specifically, I study the use of webpage content, rather than personal data, for ad targeting—a strategy known as contextual advertising. My thesis explores methods for understanding online content using Natural Language Processing (NLP) and the impact of online contexts on advertising effectiveness. 
     <br><br>
    <!-- My thesis includes articles on which explores (i) how natural language processing (NLP) can be leveraged to analyze online content, (ii) examines the impact of online contexts on advertising effectiveness and (iii) the implications on consumers and advertisers of contextual versus personal advertising. <br><br> -->

    Before my PhD, I earned a B.Sc. in Industrial Engineering and Management and an M.Sc. in Computer Science and Machine Learning from KTH Royal Institute of Technology in Stockholm. <br><br>

    On this website you will find a summary of my research and links to the articles that will constitute my PhD thesis.    
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

Motivated

Here i provide a summary of my researchetc.

Together my ads create insights on:  
- (i) How AI-driven contextual advertising can be implemented technically using methods such as NLP.  
- (ii) How media contexts influence how ads are perceived.  
- (iii) The societal and consumer implications when AI decides who marketing messages are targeted to.
- (iv) How should marketers choose advertising strategies with regards to AI, data, regulations .....

## **Research categorization, aims and questions**

The articles in my thesis fall into 3 main categories.

1. **Natural Language Processing (NLP) work** (Articles 1 & 2) <br>
  - NLP-techniques/systems for understanding the topics and sentiments of online content, where ad targeting is one application. Specifically: I use LLMs to extract fully contextualized aspect-sentiment pairs, dubbed \emph{opinion unbits} in online reviews (Article 1 & 2).  
  - Demonstrate the performance of opinion units as a chunking strategy in opinion search (article 1) and topic modelling (Article 2). Topic modelling of opinions can provide picture of consumers' opinions and regression of topics unto business metrics and outcomes  (Article 2).

2. **Controlled experiments with online participants** (Articles 3 & 4) <br>
   - How does the surrounding media context influence how online ads are perceived (Article 3 & 4)?
   - Should advertisers avoid advertising alongside negative contexts? (Article 4)

3. **Review, conceptual, and technical commentary articles** (Articles 5 & 6) <br>
   - How can/should AI from a technical perspective be applied within online advertising targeting? Examining methodologies, applcations for effective and non-privacy infringing advertising (Article 5)  
   - What consequences does AI have on consumers, and societal implications? (Article 5)  
   - How should marketers choose advertising strategies with regards to AI, data, regulations... (Article 6)

<!--
# Articles listed
Link to an article.
[Download the Opinion Units PDF]({{ '/assets/articles/opinion_unit.pdf' | relative_url }}) -->

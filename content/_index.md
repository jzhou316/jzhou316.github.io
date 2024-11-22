---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-4
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
#      button:
#        text: Download CV
#        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['0px', '0', '0px', '0']
  - block: markdown-wide
    content:
      title:
      subtitle: ''
      text: |-
        **Hello! ☃**

        I am an Assistant Professor at Stony Brook University, with appointments in <a href="https://www.cs.stonybrook.edu/admissions/Graduate-Admissions-Data-Science">Data Science</a>, the <a href="https://www.stonybrook.edu/commcms/ams/">Department of Applied Mathematics & Statistics</a>, and the <a href="https://www.cs.stonybrook.edu/">Department of Computer Science</a>. I do research in natural language processing (NLP) and machine learning (ML).
    
        Previously I was a Research Assistant Professor at the <a href="https://www.ttic.edu/">Toyota Technological Institute at Chicago (TTIC)</a>, situated on the University of Chicago <a href="https://x.com/TTIC_Connect/status/1696932798840570113?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Etweet">campus</a>.
        I obtained my Ph.D. from the <a href="https://seas.harvard.edu/">School of Engineering and Applied Sciences (SEAS) at Harvard University</a>, affiliated with the Natural Language Processing (NLP) group at <a href="https://nlp.seas.harvard.edu/">Harvard</a>/<a href="https://rush-nlp.com/members/">Cornell</a>. I am fortunate to be advised by Professor <a href="https://rush-nlp.com/">Alexander (Sasha) Rush</a>, currently at Cornell University. I have also worked with Professor <a href="https://minlanyu.seas.harvard.edu/">Minlan Yu</a> at Harvard on ML applications in networks and cybersecurity.
        I obtained an M.A. degree in <a href="https://statistics.fas.harvard.edu/">Statistics</a> from Harvard University. Prior to Harvard, I received my B.S. degree in EE from Tsinghua University.

    design:
      # css_style: "background-color: #f0f0f0; padding: 10px;"
      # css_class: "markdown-wide"        # this does not seem to work
      columns: '1'
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['8px', '0', '10px', '0']
  - block: markdown-wide
    content:
      title:
      subtitle: ''
      text: |-
        ### Research
    
        *My previous <a href="https://sites.harvard.edu/jzhou/">webpage is here</a> for reference of past research and projects.*
    
        My primary research interests lie in the areas of natural language processing (NLP) and machine learning (ML). The ultimate goal is to build general intelligent machines that can understand, interact, and help human beings on a wide variety of tasks with **trustworthiness** and **efficiency**. I am glad to see LLMs are bringing us one step closer 🤔

        I am broadly interested in understanding and improving state-of-the-art deep learning models such as (large) language models (LLMs), on a variety of aspects such as efficiency, knowledge represention and manipulation, memorization, factualness, security, fair evaluation, reasoning and planning, as well as multimodality.
        Check <a href="/research/">Research</a> for more details.
        Feel free to reach out to collaborate on any interesting problems.

    design:
      # css_style: "background-color: #f0f0f0; padding: 10px;"
      # css_class: "markdown-wide"        # this does not seem to work
      columns: '1'
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['10px', '0', '0px', '0']
  - block: markdown-wide
    content:
      title:
      subtitle: ''
      text: |-

        {{< spoiler text="Prospective Students" >}}
        {{% callout note %}}
        **Prospective Students:**
        If you're interested in working with me, feel free to reach out with a brief introduction, an overview of your research background, and any problems or ideas you’re currently exploring. I am looking for highly motivated students (in any stage) with strong technical skills in programming and mathematical reasoning. Strong communication and writing skills are equally important, as our work involves documenting and presenting research findings effectively.
    
        Our research focuses on advancing cutting-edge techniques in NLP and ML, so you should be prepared to write a substantial amount of code daily and conduct extensive experiments. I deeply value curiosity-driven minds, rigorous thinking, and creative problem-solving—essential qualities for producing impactful and innovative research that shapes a more exciting future.
    
        I am actively looking for outstanding Ph.D. applicants who meet the above criteria. If you are interested, consider applying to the Ph.D. programs in <a href="https://www.cs.stonybrook.edu/admissions/Graduate-Program">Computer Science</a>, <a href="https://www.cs.stonybrook.edu/admissions/Graduate-Admissions-Data-Science">Data Science</a>, or <a href="https://www.stonybrook.edu/commcms/ams/graduate/_resources/applying-to-the-AMS-grad-program.php//">Applied Mathematics & Statistics</a> (if your background is in mathematics or statistics). Be sure to mention my name in your application, and feel free to reach out after applying if there is a strong alignment with your interests and expertise.

        Please note that I cannot guarantee a reply to every inquiry (apologies), and sometimes my response may be (very) delayed.
        {{% /callout %}}
        {{< /spoiler >}}

    design:
      # css_style: "background-color: #f0f0f0; padding: 10px;"
      # css_class: "markdown-wide"        # this does not seem to work
      columns: '1'
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0', '0px', '0']
---

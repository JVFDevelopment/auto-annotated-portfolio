---
type: PageLayout
title: About
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg4.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: >+
      ## Hi, I’m Joseph, a dedicated and passionate software engineering student
      with a deep interest in creating innovative and functional digital
      solutions. My journey into the world of software development started with
      curiosity and a desire to understand how the technology we use every day
      works. Over time, that curiosity transformed into a full-blown passion,
      leading me to pursue software engineering as a career path.


      I have experience in a wide range of programming languages, including
      Python, JavaScript, HTML, and CSS, and I’ve worked on various projects
      that demonstrate my versatility and creativity. One of my core strengths
      is front-end development, where I focus on building interactive,
      user-friendly websites and applications that provide a seamless
      experience. From real-time quiz games to dynamic web pages, I enjoy the
      challenge of turning ideas into reality through code.


      While front-end development is a big part of what I do, I’m always eager
      to expand my skill set. I’ve dabbled in backend development, exploring Lua
      for game development on Roblox, and experimenting with Rust for building
      efficient systems. My projects, like **Clicker Gods**, **Crypt
      Crusaders**, and **minimod**, showcase my ability to adapt and work across
      different technologies while delivering high-quality results.


      I’m a firm believer in learning by doing, which is why I constantly push
      myself to take on new challenges. Whether I’m building a Discord bot to
      help server admins or creating a game that engages players, I’m always
      looking for ways to improve my skills and solve real-world problems. As I
      continue to grow in my software engineering journey, I aim to develop
      projects that not only work well but also bring value to users and
      communities.


      Outside of coding, I enjoy collaborating with others, whether it’s through
      open-source contributions or working on team-based projects. I believe
      that the best solutions often come from a blend of perspectives and
      skills, and I’m always open to learning from others. This collaborative
      spirit drives me to be an active member of various developer communities.


      Thank you for visiting my portfolio! Feel free to explore my projects, and
      if you’d like to connect, don’t hesitate to reach out. I’m always excited
      to discuss new ideas, collaborate on projects, or simply share insights
      about the world of software development.

    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: LabelsSection
    colors: colors-f
    subtitle: 'Skills:'
    items:
      - type: Label
        label: HTML
      - type: Label
        label: JavaScript
      - type: Label
        label: Python
      - type: Label
        label: C++
      - type: Label
        label: Netlify
      - type: Label
        label: Pancakes
      - type: Label
        label: C++
      - type: Label
        label: Swift
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: TextSection
    variant: variant-a
    subtitle: 'Contact:'
    colors: colors-f
    text: |
      [thisismyemail.@myemail.me](mailto:thisismyemail.@myemail.me)
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: ContactSection
    backgroundSize: full
    title: "Let’s talk... \U0001F4AC"
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Tell me about your project
          isRequired: true
          width: full
          type: TextareaFormControl
        - name: updatesConsent
          label: Sign me up to recieve my words
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---

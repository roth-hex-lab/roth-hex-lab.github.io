---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: |
        
        {{< figure src="logo_hex-petrol.png" caption="" >}}
        HEX Lab
      subtitle: About Us
      text: |
        ### <i>Imagineering novel languages for the communication between human(s) and machine(s)</i>

        Established in 2021 and relocated to the Technical University of Munich (TUM) in 2023, the Human-Centered Computing and Extended Reality Lab aims to pioneer new technologies to enhance medical care and healthcare. We pursue fundamental, translational, and radical blue-sky research to improve medicine for patients and healthcare professionals.

        We adopt a holistic perspective on machine intelligence, emphasizing AI-driven technologies that enable meaningful collaboration between humans and machines. Therefore, we operate at the intersections of human-computer interaction, artificial intelligence, extended reality, robotics, and medicine. Exemplary research areas include AI-based assistance systems for surgical procedures, systems for diagnosing diseases and disorders, telepresence procedures, and robot-assisted rehabilitation measures. 

        We perform our research integrative as part of [TUM](https://www.tum.de/)'s School of Medicine and Health, [TUM](https://www.tum.de/)'s School of Computation, Information, and Technology, and the TUM University Hospital Department Clinical Medicine, affiliated with the [Clinic for Orthopedics and Sports Orthopedics](https://ortho.mri.tum.de/klinik.html).
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'

      
  - block: collection
    id: news
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: compact
      columns: '2'
  

  - block: people
    content:
      title: People
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - Head
        - Senior Research Scientists
        - Researchers
        - External Affiliated Researchers
        - Team Support
        - Visitors
        - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      # Show user's social networking links? (true/false)
      show_social: false
      # Show user's interests? (true/false)
      show_interests: true
      # Show user's role?
      show_role: true
      # Show user's organizations/affiliations?
      show_organizations: false

  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        # Folders to display content from
        folders:
          - projects
        # Only show content with these tags
        tags: []
        # Exclude content with these tags
        exclude_tags: []
        # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
        kinds:
          - page
      text: |
        Our research is centered around the understanding, design, development, and evaluation of computing solutions and human-machine interfaces that improve the way we interact with, work with, and communicate through machines. A majority of our research considers AI driven Extended Reality user interfaces in the context of physical and mental health, such as Virtual-, Mixed- or Augmented Reality systems. Examples of these are assistive technologies for medical procedures or systems to assess and diagnose pathologies and disorders.

        To do so, we strive for foundational, translational, and radical scientific contributions with high methodological and experimental quality. Our research is inspired by multiple disciplines, including but not limited to Computer Science, Psychology, Design, Medicine, and Neuroscience. We incorporate methods from these disciplines, such as computer vision, computer graphics, artificial intelligence, and user-centered design in a broad methodological bandwidth to support our research goals. We closely interact with partners from medicine and industry to incorporate different perspectives.
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
      # Default portfolio filter button
      # 0 corresponds to the first button below and so on
      # For example, 0 will default to showing all content as the first button below shows content with *any* tag
      default_button_index: 0
      # Filter button toolbar (optional).
      # Add or remove as many buttons as you like.
      # To show all content, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the button toolbar, delete the entire `buttons` block.
      #buttons:
      #  - name: All
      #    tag: '*'
      #  - name: Deep Learning
      #    tag: Deep Learning
      #  - name: Other
      #    tag: Demo
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      # Choose a listing view
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  - block: collection
    id: publications
    content:
      title: Publications
      subtitle:
      text:
      count: 4
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: publication
    design:
      view: compact
      columns: '2'

  - block: markdown
    id: teaching
    content:
      title: Teaching
      #subtitle: About Us
      text: |
        ### Topic Areas

        We offer theses in various research areas. Applications for thesis are considered to the dates 1st of April for the Summer Semester and 1st of October for the Winter Semester. We offer topics in the following areas:

         - Human-Centered Computing / Human-Computer Interaction
         - Machine Intelligence / Artificial Intelligence
         - Computer Vision / Neural Rendering / Deep Learning
         - Extended Reality
         - Rendering, Interfaces & Interactivity
         - Robotics & Exoskeletons
         - Digital Health

        If you are interested, please send your transcript of records, CV and motivation to the respective supervisor with CC to hex-thesis.ortho@mh.tum.de.


        ---
        ### Lectures and Seminars

        **Exergames in Medicine and Health (SS)**\
        This course deals with the theory, design, engineering and development of exergames. In the course, students will be provided with theoretical game-design, gamification and medical foundations and work in small groups to realize working exergame prototypes. Exemplary project themes could be:

        - Designing exergames for rehabilitation and physiotherapy
        - Designing gamified approaches for performance optimization in sports
        - VR supported simulations for patients with motor impairments

        The course is designed in an interactive project format. Based on initial discussions and theoretical input, students research, design, develop, and evaluate solutions in the form of projects and studies in small groups following user-centered design and agile software engineering principles.

        More information can be found [here](https://campus.tum.de/tumonline/ee/ui/ca2/app/desktop/#/slc.tm.cp/student/courses/950762452?$scrollTo=toc_overview).

        **XR: Virtual-, Mixed-, and Augmented Reality (WS)**\
        In this lecture, students will expand their knowledge of advanced topics in virtual, augmented, and mixed reality. Key topics include among others:
        - Real-time interactive systems, avatars, and virtual embodiment
        - Social XR, collaborative environments
        - Advanced 3D interfaces and visualization techniques
        - Cross-reality and environment reconstruction
        
        In an accompanying practical exercise, ythey will gain practical experience in developing advanced XR application.
        
        Registration via [TUMonline](https://campus.tum.de/tumonline/ee/ui/ca2/app/desktop/#/slc.tm.cp/student/courses/950804473?$scrollTo=toc_overview)

        **Computer Vision in the Operating Room (WS)**\
        This seminar focuses on the latest methods in computer vision and deep learning for applications in the operating room. The course includes individual paper reviews and interactive presentations, helping students not only to develop technical expertise but also to build scientific communication and discussion skills.

        More information can be found [here](https://campus.tum.de/tumonline/ee/ui/ca2/app/desktop/#/slc.tm.cp/student/courses/950793211?$scrollTo=toc_overview).


    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'

  - block: markdown
    id: vacancies
    content:
      title: Open Positions
      subtitle: ""
      text: |
        ---
        ### Student
        <mark>Open Position:</mark> We are looking for a lab assistant (20hours a week) to support lab activities. Computer Scientist, strong coding and demo skills, preferably background in robotics or augmented / virtual reality.

        ---
        ### PhD / Postdoc
      If you have a strong research / study background in the areas of XR, HCI, Computer Vision, Medical Engineering, or Robotics please drop us a mail and we'll get back to you.

    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle: ''
      text: |
        Prof. Dr. Daniel Roth<br>
        Technical University of Munich<br>
        Klinikum rechts der Isar<br>
        Machine Intelligence in Orthopedics<br>
        Human-Centered Computing and Extended Reality Lab<br>
      # Contact details - edit or remove options as needed
      # email: ''
      # phone: 888 888 88 88
      address:
        street: Trogerstrasse 10
        city: Munich
        postcode: '81675'
        country: Germany
        country_code: DE
      directions: |
        Find us on the third floor.<br>
        Please direct postal deliveries to <i>c/o Fritz Seidl, Ismaninger Str. 22</i>
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: Twitter
          link: 'https://twitter.com/rothnroll'
      # Automatically link email and phone or display them just as text?
      autolink: true
      # Coordinates to display a map - set your map provider in `params.yaml`
      coordinates:
        latitude: '48.1363964'
        longitude: '11.6023856'
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'

---

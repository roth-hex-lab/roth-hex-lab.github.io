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
      subtitle: |
        About Us
        {{< figure src="team.jpg" caption="" >}}
        {{< figure src="Logo5.png" caption="" >}}
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
        - Director
        - Senior Research Scientists
        - Researchers
        - Affiliated Researchers
        - Student Assistants
        - Visiting Researchers
        - Alumni
      sort_by: Params.first_name
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
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.


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

  - block: portfolio
    id: teaching
    content:
      title: Teaching
      filters:
        # Folders to display content from
        folders:
          - teaching
        # Only show content with these tags
        tags: []
        # Exclude content with these tags
        exclude_tags: []
        # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
        kinds:
          - page
      text: |
        ### Topic Areas

        We offer theses in various research areas. Applications for thesis are considered to the dates 1st of April for the Summer Semester and 1st of October for the Winter Semester. We offer topics in the following areas:

         - Human-Centered Computing / Human-Computer Interaction
         - Machine Intelligence / Artificial Intelligence
         - Computer Vision / Neural Rendering / Deep Learning
         - Extended Reality / Augmented Reality / Virtual Reality
         - Rendering, Interfaces & Interactivity
         - Robotics & Exoskeletons
         - Digital Health

        If you are interested, please click on 'Apply' and check out the application details for a thesis or project with us.
        
        ### Lectures and Seminars
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

  - block: portfolio
    id: vacancies
    content:
      title: Apply
      filters:
        # Folders to display content from
        folders:
          - vacancies
        # Only show content with these tags
        tags: []
        # Exclude content with these tags
        exclude_tags: []
        # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
        kinds:
          - page
      text: |
        
        ### 
        Interested in working or researching with us? Find out more below. Depending on your career level, we offer different options.
        
      # *Currently we offer the following positions:* 

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
      columns: '1'
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle: ''
      text: |
        Prof. Dr. Daniel Roth<br>
        Technical University of Munich<br>
        TUM University Hospital<br>
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

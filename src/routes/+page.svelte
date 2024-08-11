<script>
  import Header from '../lib/components/Header.svelte';
  import Technologies from '../lib/components/Technologies.svelte'; 
  import ProfessionalHistory from '../lib/components/ProfessionalHistory.svelte';
  import ShippedTitles from '$lib/components/ShippedTitles.svelte';
  import Education from '$lib/components/Education.svelte';
</script>

<Header title="Mandi Booley" />
<p>Hello! I am a software engineer with a background in game design (9 years) and web development (5 years). The end user is at the center of everything I do. ♥️</p>

<hr/>

<h2>Experienced with</h2>
<Technologies />

<hr/>

<h2>Professional History</h2>
<ProfessionalHistory 
  position={"Software Engineer"} 
  companyName={"Seeq"} 
  startDate={"Jan. 2022"}
  endDate={"Present"}
  accomplishments={[
    "Designed and implemented front-end features for industrial analytics app that scored highly in user surveys",
    "Modernized aspects of the front-end codebase",
    "Mentored team intern (6-month internship)",
    "Took ownership of i18n and worked with external vendor to refine process",
    "Lead Frontend Guild and gave talks on testing, interesting bugs, books, and more"
  ]}
  />

  <ProfessionalHistory 
  position={"Software Engineer"} 
  companyName={"Expedia"} 
  startDate={"Jan. 2015"}
  endDate={"Aug. 2017"}
  accomplishments={[
    "Lead an embedded apprenticeship project working with a pair of college freshmen to add new photo upload and management functionalities to Ember-based app",
    "Identified root causes of various date picker and timezone issues, implemented improvements",
    "Contributed to the design and flow of new user onboarding experie",
    "Debugged, improved, and added to the project's automated tests (Karma, Ruby/Cucumber)",
    "Regular contributor to project-specific and onboarding documentation"
  ]}
  />

  <ProfessionalHistory 
  position="Independent Web Developer" 
  companyName="Self-Employed" 
  startDate="2013"
  endDate="2021"
  accomplishments={[
    "Designed and built original 'link checker' web app using React, socket.io, node.js, and the Amazon Product Advertising API - Amazin' Affiliate Link Checker (GitHub)",
    "Designed and built original 'course reviews' web app in Angular and node.js that scrapes data from a Google spreadsheet and displays it in a user-friendly responsive design website - OSU CS Course Explorer (GitHub)",
    "Developed and maintained personal WordPress sites, including TowerSecrets.com (GitHub) and DIYCraftPhotography.com",
    "Customized Genesis child theme and WordPress loop to meet the needs of several different websites"
  ]}
/>

<ProfessionalHistory 
  position="Game Designer" 
  companyName="Disney Social" 
  startDate="February 2013"
  endDate="April 2014"
  accomplishments={[
    "Collaborated with client and server engineers to develop asynchronous multiplayer features to create a consistent experience for players",
    "Assisted in design of studio-wide data management tool",
    "Led UX team on improvements that significantly improved product's performance in UX tests",
    "Designed new user onboarding experience for Facebook game"
  ]}
/>

<ProfessionalHistory 
  position="Lead Designer" 
  companyName="Glu Mobile (formerly Griptonite Games)" 
  startDate="December 2008"
  endDate="November 2012"
  accomplishments={[
    "Independently developed Flash ActionScript prototype to help secure project greenlight and demo project idea to team",
    "Authored Java-based string processing and table data tool",
    "Oversaw combat balancing, level design, and overall game scoping",
    "Wrote detailed technical documents detailing gameplay features for the team's programmers",
    "Wrote pitch decks and overarching game design documents"
  ]}
/>

<ProfessionalHistory 
  position="Lead Artist/Designer" 
  companyName="Webfoot Technologies, Inc." 
  startDate="April 2006"
  endDate="December 2008"
  accomplishments={[
    "Designed and implemented ActionScript game menus for Nintendo DS titles",
    "Collaborated with programming team to develop features and tool support",
    "Scripted gameplay events and cutscenes",
    "Modeled and animated 3D low-poly characters, props, environments",
    "Rendered 2D character portraits and backgrounds"
  ]}
/>

<hr/>

<h2>Projects</h2>
Coming soon

<hr/>

<h2>Education</h2>
<Education />

<hr/>

<h2>Shipped Titles</h2>
<ShippedTitles
  titles={[
    "Marvel Avengers Alliance Tactics (2014) - Facebook",
    "Enchant U (2012) - iOS/Android",
    "Marvel Super Hero Squad: Comic Combat (2011) - Wii, PS3, XBOX 360",
    "Shrek 4 Forever After (2012) - Nintendo DS",
    "The Penguins of Madagascar (2010) - Nintendo DS",
    "Solitaire Mahjong - Ancient China Adventure (2009) - Nintendo DS",
    "Dream Day Wedding Destinations (2009) - Nintendo DS",
    "American Girl: Kit Mystery Challenge! (2008) - Nintendo DS",
    "American Girl: Julie Finds a Way (2007) - Nintendo DS",
    "My Little Pony: Pinkie Pie's Party (2008) - Nintendo DS",
    "My Little Pony: The Runaway Rainbow (2006) - PC"
  ]}
/>
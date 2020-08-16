# VirtuaLab

A cutting-edge multifaceted immersive virtual science lab right at your fingertips.

To access the landing page, [click here.](https://feliren88.github.io/VirtuaLab/)

## Inspiration

The awakening of the recent COVID-19 pandemic has crippled multiple sectors that are essential parts of living. One of such sectors is the Science, Technology, Engineering and Mathematics (STEM) education industry. In light of this event, students, teachers and researchers alike have been denied access to their so-called ‘Garden of Eden’ that is crucial to them, their laboratories. The term ‘Work from home’ has now taken precedence and although this has made living and working somewhat manageable for some, we could not say the same for others, especially those in STEM. Being tethered to the internet and online resources alone is not meeting all the requirements of the members of STEM, such as the need for a full-blown laboratory.

We noticed that this issue was evident in our alma mater, Monash University and decided to investigate further by conducting questionnaires in the form of a survey. In respect to Garuda Hacks, we narrowed our demographic to Indonesians pursuing tertiary education locally and abroad. Some of the key problems faced by our demographic:
- Conducting laboratory experiments may require costly equipment and apparatuses (e.g. platinum electrodes in electrolysis).
- Certain laboratory experiments may be dangerous, especially those involving materials that are corrosive, explosive, radioactive, etc.
- Radioactive materials are also expensive and may need to be replaced from time to time (depending on the half-life of the materials concerned – some such as iodine-131 has a half-life of a few minutes, meaning that they have to be replaced often).
- Storing hazardous materials may be costly.
- Not all schools/educational institutions have access to laboratories or laboratory equipment, especially in rural areas given the high cost of setting up and maintaining a laboratory. These include licensing issues as well.
- Certain schools may not store or use laboratory equipment properly and may lead to some form of damage (e.g. contaminated chemicals, zero-errors on measuring equipment etc.).
- Laboratory equipment may be outdated. Although in certain places school curricula may also be similarly outdated, this can potentially cause problems if the curricula is updated.
- Although not fundamental to the experiments itself, some students may find it uncomfortable to work in the laboratory due to malfunctioning air conditioning or projectors.
The need for the presence of a qualified laboratory technician at all times also seems to be an influencing factor. 

## What It Does

VirtuaLab stays true to its name in that it puts a completely immersive Laboratory Environment in Virtual Reality right to your fingertips. Although it was engineered for the members of STEM education for the sake of Garuda Hacks, it is truly an innovation by us to everyone keen in STEM and wish to conduct experiments & more with our multifaceted laboratory modules.

**Key features:**
- A fully interactable lab environment for you to do your experiments.
- A screen to play videos about how to conduct the experiment. Teachers and other members of the teaching staff may upload their own videos as well.
Videos may include other technical details about the experiments when conducted in the real world (e.g. hazards that one must consider). This helps students to transfer their skills from this online laboratory to the real world.
- Seamless integration between platforms.

## How We Built It

Our implementation consists of the web pages for users to understand our solution and the labs. 

The web pages consist of landing page, subject page and lab pages. 
[Our web page can be seen here.](https://feliren88.github.io/VirtuaLab/)

In this minimum viable product, we have 2 labs. The chemistry lab is responsible to set up an environment for qualitative testing while the biology lab is used for flower dissection. 

In the qualitative testing lab, we currently simulate the test for cations, specifically for the reaction on NaOH+Zn<sup>2+</sup>. To interact with the lab, click the sign on the whiteboard. The interactivity was done by using state machine, the visual programming platform within Amazon Sumerian.

We use Blender to create the 3D assets for test tube and the container for NaOH. These assets are used for Qualitative testing lab.

## Challenges We Ran Into

Being first timers at working with Virtual Reality based solution for the Hackathon, we had to take some time familiarising ourselves with different softwares (we found Amazon Sumerian to best suit our need). 

It was especially difficult to not prepare anything beforehand except for brainstorming our ideas as per the Hackathon guidelines.

Being perfectionists, we had to re-complete science course lessons and study laboratory environments to fully understand the laboratory modules we were building to ensure our laboratories had a more accurate representation of the actual physical laboratories.

Social distancing and border lockdowns due to the pandemic has restricted us to keep track of work and communicate freely, so we had to get creative by making schedules and using Agile Scrum methodologies to keep each other in check and conduct meetings online.
- Poor internet connection and stability increases the difficulty of communication as well.

With no expertise in 3D modelling, we picked up Blender to quickly learn to build our assets within Amazon Sumerian. Online 3D models required payments, so once again we had to get creative.

The lack of tutorials for Amazon Sumerian from other developers (unlike Unity). The tutorials were mainly published by AWS documentations, so it was a challenge for us to fully utilize the tool itself.

Due to the time constraint, we didn’t manage to have all the modules fully functional within Amazon Sumerian, but we managed to still produce a great minimum viable product (MVP).

## Accomplishments That We Are Proud Of

Producing a fully functional Laboratory Environment in Virtual Reality seemed impossible but having accomplished it, we knew we had to give credit where credit is due.

After planning to provide only 1 completed laboratory module for the MVP, we are proud to have successfully implemented 2 laboratory very technical laboratory modules as prototypes.

It was very important to us to be honourable and stay true to the guidelines of the Hackathon by only working during the allocated time, which initially worried us that the lack of time may affect our productivity but being a strong team of close friends, we managed to successfully implement most of our ideas.

The Chemistry laboratory module for qualitative testing is fully functional as per our expectations and the Biology laboratory module served as a bonus and a surprise added module much to our surprise.

Given the constraints we are also proud that on top of the core product, we managed to build a full-blown website with landing pages, laboratory modules and multiple features and functions to assist our users to seamlessly navigate through VirtuaLab.

All that being said, we are extremely satisfied and proud with our final minimum viable product (MVP).

## What We Learned

Being newbies at Virtual Reality and still being able to produce an amazing MVP taught us that no matter how intimidating a new venture might seem, we should be sure to give it our best.

It was an exhilarating experience to have been given the opportunity to work with our closest friends in producing a product that could change the lives of our users.

Being Computer Science students and graduates, we learnt the importance of additional aspects such as design implementation and usability needed to be paid attention to for a successful product implementation. We also turned to the problems faced by society to produce a solution that caters them the best.

We adapt ourselves to effectively collaborate remotely in the given time by conducting online meetings, research and constantly keeping each other informed.

We learnt how to utilise Bootstrap templates and HTML and CSS for fine tuning, which helped us with quick prototyping for our MVP.

We picked up Blender in a short period of time to help us with 3D modelling given that most 3D modelling tools require payment.

A successful Venture Capitalist once personally told us that having a great team is as important if not more important than having a great idea and in this Hackathon we learned that to be true because without any one of us, we would not have been able to accomplish what we have today.

## What's Next for PocketAnalyst

Our vision for VirtuaLab is to provide a sustainable solution that alters the lives of users who experience it. Although VirtuaLab was conceived due to the needs posed by the current pandemic, it solves problems that date back decades and still continue being a pain point for laboratory users. We also implemented additional features that provide users  Which is why the brilliant solution we have proposed is not just a fluke, but an idea that comes by once in a lifetime (and yes, we’re looking for investors).

- We can scale it into more lab modules from a variety of subjects.
- Developers would be able to create their own lab modules.
- All modules created will also be checked for scientific correctness to prevent people from uploading experiments that show scientifically incorrect results.
- We may support multiple languages for the end product (Bahasa Indonesia, English, etc) due to the importance of localization.
- A system of user accounts may be implemented for the system. We will be thinking of using Cotter for this purpose of passwordless login and integration with biometrics.
- We can have a virtual avatar as a guide in Bahasa or English how to demonstrate step-by-step the lab module for education purposes. This is for attractiveness and usability.
- Multiple users will be able to use the same virtual environment. Each user will have their own interactable virtual avatar as well. This enables lab activities that require group work.
- To do this, we can increase the size of labs to accommodate a minimum of 20 to 30 students in the same environment (so that it looks similar to a high school/university laboratory environment).
- Option for third-person view when personal virtual avatars are available. Some people may find it more comfortable to use a third-person view of their avatar when communicating with their peers.
- We can integrate the system into some universities for research purposes (Ex: Electrical Engineering research that may require an oscillator, etc).
- We can extend this to multiple platforms other than PCs, especially mobile and VR devices.
- The scalability of the system would be quite large, where there are thousands of modules per subject. A search feature would be useful in this case.
- Each module will have a unique module ID
- Module developers may choose to include tags for modules so that one can search for tags instead (e.g. for experiments of rates of enzyme reaction, one can search for “[chicken liver] [catalase] [hydrogen peroxide]”.)

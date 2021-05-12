# Kasey Purvor
***Mechanical Engineering Portfolio*** 
___
## Contents:   
*In reverse order - most recent first* 
   
   **Servotest LTD**
  > - Ballistic Screens 
  > - Contamination Study
  > - Banjo Bolt Failure Investigation 
  > - Ratchet Safety Mechanism 
  > - Safety Screen    

  **Overview LTD**
  > - Torque Sensor  
  > - Motor Test Rig   
  > - 3D Printer    

  **University Work**    
  > - Group Design & Make - Plasma Surface Modification   
  > - Final Year Project - Glass Viscometry   
  > - Research Project - Megabatteries As Grid Storage Sollution 
___
## My Work At Servotest
My most recent employement began during the first lockdown as was challenging for a number of reasons. As the company was unprepared for home working, I was unable to be trained in the heavily regulated hydraulics. Therefore I seeked out problems that were novel to the company, and therefore nobody was better suited than me through experience. I am proud hopw I handled this period and thrived performing work that had many new concepts. The work I did had very little guidance, and required me to be resilliant, patient, dependable and an strong self starter. The following outlines some of the work I did during my time there. 

### Ballistic Screens
> During testing of a large hydraulic piston, a fluid carrying component failed. The failed component was ejected at speed and punctured a metal ceiling. An investigation into
> the component was launched [see here](#banjo-bolt) and the design of adequate safety screens was comissioned. Both were delagated to me.  
>
> I needed the mass & velocity of the projectiles. I began by identifying the largest & longest projectile (as this would be the worst case) and based my
> analysis on this. I then studied the ***pressure test safety*** document for a way to model the acceleration (figure 1). Along with the eqautions of motion (figure 2) I came
> up with a calculation for determining the escape velocity of the component (figure 3) by the large red arrow. 
> 
> ![ballistic_screen_acceleration](https://user-images.githubusercontent.com/67878899/117819319-56a29700-b261-11eb-84ff-8f0abf544b16.png)
>
> With the escape velocity of the projectile known, I then applied the data to the perforation theory of polycarbonate(figure 4). Figure 5 shows the
> experimental data obtained with this theory.The red arrow shows where the projectile fits the data, you can see it reccomends a thickness of about 8mm. 
> 
> ![ballistic_screen_perforation](https://user-images.githubusercontent.com/67878899/117823650-9ec3b880-b265-11eb-9f80-88f68c65f74b.png)
> 
> With all of this determined I opted to design the screens at 10mm thickness. The design drawing can be seen below. 
> 
> ![ballistic_screen_drawing](https://user-images.githubusercontent.com/67878899/117833509-4d6bf700-b26e-11eb-9e9b-7116ec6adb02.jpg)

___
## Contamination Study 
> After some hydraulic pistons were shipped back from our parent company in China with heavily worn seals, investigation showed there was a mysterious powder contaminant in the
> hydraulic fluid (image below). It was wearing away the seals as they moved. I was tasked with determining what the contamination was and where it was coming from.
> 
> ![seal_contamination ](https://user-images.githubusercontent.com/67878899/117832715-a38c6a80-b26d-11eb-827e-d2d879ed4e76.jpg)
> 
> After some research into microsopy I opted to have a sample analysed by a scanning electron microscope. This would allow me to image the particles and have their elemental 
> composition determined through spectroscopy. After a trip to Surrey University I had the results of several scans to analyse. You can see the image as well as the spectrographic
>  information of the 4 particles highlighted below. 5 of these scans were performed all with similar results. 
> 
> ![seal_contamination_results](https://user-images.githubusercontent.com/67878899/117832919-d171af00-b26d-11eb-82e7-3aec3cc0b70b.png)
> 
> The results showed there were 3 predominant elements and 2 types of particle. They were silicon, aluminium and oxygen. 
> With the seals thewmselves made of silicon therefore these were the source of silicon, leaving aluminium and oxygen. I knew that Aluminium oxide (aluminium + oxygen) is a
> common  grit blasting medium, which is a technique used by our parent company in China. We therefore deduced that the pistons had been left exposed while grit blasting had
> occured and  the debris had landed on the piston and contaminated the oil. 

## Banjo Bolt
> Commisioned following the failure of a bolt carrying high fluid pressure, this was the projectile from the [ballistic screen](#ballistic-screen) work. An investigation was    > performed to find out how to avoid a repeat. The bolt was modelled and its operating conditions were applied to a simulation, including fluid pressure and tightening torque.
> A stress map can be seen below along with the model below
> 
> ![banjo_bolt_model](https://user-images.githubusercontent.com/67878899/117842751-24e7fb00-b276-11eb-9a30-cea3e79511d1.png)
> 
> The simulation showed that there were obvious weak points in the bolt, where the 2 through holes intersected. This was a design flaw by the manufacturer. 
> As the fuild pressure was constant, the only variable we could control was the torque that the bolt was tightened to. As the tightness of the bolt translates into tension in 
> the bolt shaft. The theory for this is shown below
> 
> ![banjo_bolt_tension_equations](https://user-images.githubusercontent.com/67878899/117846027-f7e91780-b278-11eb-8e2d-e16f6059ec49.png)
> 
> With this known, a huge number of iterative simulations were conducted. Each trying to determine what was the ideal tightening torque for the bolt. The results of the 
> simulations are shown below. 
> 
> ![banjo_bolt_simulation_results](https://user-images.githubusercontent.com/67878899/117846473-6201bc80-b279-11eb-94e9-21f33b668a73.png)
> 
> The results showed that the existing bolt was capable of 10Nm of tightening torque, making it unusable as the minimum required was 20Nm. It also revealed that if the bolt
> only had 1 through hole, as opposed to 2, that the bolt would be usable as it could sustain 20Nm 
> 
> 

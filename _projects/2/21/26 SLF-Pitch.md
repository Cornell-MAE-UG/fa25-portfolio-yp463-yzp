---
layout: project
title: Open Design Project
image: /assets/images/photos/spotted-lanternfly.jpg
---

For my Introduction to Mechanical Design class, we were asked to work in small teams to come up with a mechanism to contribute to the fight against an invasive insect in North America called spotted lanterfly (SLF) as a part of our **Open Design Project**. We were tasked with designing a device that could aid the grape juice and wine industries specifically, as SLF are particularly drawn to grape vines and often contaminate grape harvests. For this project, we collaborated with real clients and gained insights from grape growers as well as entomologists. After coming up with a rudimentary design for our mechanism, my team created a client pitch and recieved feedback from the experts.  
After that, we built a mock-up of our design. This allowed us to better visualize our idea and get a sense of what issues might come up. We tweaked our initial idea a bit to improve the efficacy of our design and address concerns we had based on the feedback and our own observations.  
Next, we created a functional prototype and documented our process.

## **Client Pitch**


### **Wine Grape Post-Harvest Filtration** 

**Clients:** Cornell CALS Extension / E&J Gallo Winery / National Grape  

**Team Name:** Trees of Doom  

### **Spotted Lanternfly Grape Harvest Contamination**  

Spotted lanterflies (SLF) damage grape vines and also end up in the harvested mixture. SLF
contamination is of critical concern for New York State grape farmers, as federal regulation holds
that more than 0.1% foreign matter in harvested grape batches results in entire 22-ton batches of
harvest being rejected \[1\]. Contamination is tested in 1000g samples, and SLF weigh 0.5-1.0g each,
the presence of just 1-2 bugs in a batch is potentially detrimental \[1\]. An initial study found that
on average, 60% of SLF present on vines were picked up by the mechanical harvester, leading to,
on average, 289 SLF per batch—far greater than the allowable amount. **The rejection of grape
harvest batches due to foreign matter presence decreases New York state vineyard
yields and profits.**


### **Proposed Solution: mechanical filter to remove the SLF post-harvest** 

We propose to use water to separate grapes from SLF based on density (grapes sink, SLF float).
This would be accomplished via a two-sided strainer with a mechanism to remove SLF off the
water’s surface (see Figure 1).


**How it would be used:**
- Grapes are harvested as per usual
- Harvested grape + juice mixture is run in batches through the mechanical filter, which removes
any SLF.


**Why it’s better than the status quo:**
- Attempted filtration is better than no filtration
- Avoids any modifications to the harvesting process and has simple implementation
- Guarantees that once any SLF are removed, they are removed for good (instead of from the
vines before harvest when they can return).


### **Key Risks / Unknowns** 
- SLF and grapes getting crushed during harvest could affect their densities (and therefore
buoyancy and filtration).
- Our filter would ideally match the pace of the harvesting process. This introduces design and
manufacturing complexities and also requires that vineyards have space to house the filter.


### **Questions for the Client** 
1. How crushed are SLF after the grapes have been harvested? Are they mostly intact or are
they often split into small pieces such as legs and wing fragments?
2. Our idea is based on the assumption that SLF float in water and grapes sink. Is this generally
true, and is the density of SLF approximately the same across all of their body parts?
3. What is a typical grape/grape juice ratio after the grapes become crushed post-harvest?


### References and Figures
\[1\] Bekelja, K. and Russo, J. ”MAE 2250 - Spotted Lanternfly Presentation,” Cornell IPM and
New York State Integrated Pest Management, 2026.


![Figure 1](/assets/images/photos/slf-pitch-diagram.png)
*Figure 1: Prototype schematic of the proposed buoyancy-based spotted lanternfly filter.*


[Download our pitch]({{ "assets/images/pdfs/TreesofDoom_ClientOutline.pdf" | relative_url }}) in PDF format.


## **Functional Prototype** 

### **Purpose:**  
The purpose of our group creating a functional prototype was to vet our design and make sure it actually functioned as intended. We needed to figure out what components/materials we needed and how to assemble them. This is especially important for designs that have moving parts and precise tolerances. Not only did our design have to work, but it also had to deliver consistent results over multiple uses. To do this, we tested various aspects of our design and documented our process. The documentation is key to recording the results of our tests, as well as keeping record of our assembly parts and process to help us with later steps in the design process.

### **Design Tests and Results**  


**1. Rotation test**  

This test was meant to assess the ability of the handle, shaft, and base components to rotate freely
beneath the divider of the cylinder. It was performed by rotating the shaft using the handle and
observing the smoothness and ease of motion of the base. Success criteria for this test was that the
base would be able to be rotated using a non-strenuous amount of force from a human hand at the
handle, and that the mesh would not noticeably interfere with the dividers upon rotation.
The results of this test were informative. First, we observed smooth rotation of the base when low
to moderate force was applied to the handle, indicating effective tolerancing on the interface
between the base and cylinder to limit friction. Second, however, we noticed that the edges of the
mesh, particularly the epoxy connections, momentarily jammed rotation when they passed under
the dividers.  

For the next iteration, to resolve this, we plan to create an indentation in the base for the mesh to
rest within, allowing the top of the mesh to sit at the same height as the rest of the base and pass
under the divider without impeding rotation.


**2. Water retention test**
This test was meant to check the seal and water retention of the cylinder and base. It was
performed by filling the cylinder with water for 15 minutes and observing leaks in the points of
connection in the cylinder. 

The results of this test were also informative. The test showed us that the prototype was very
poorly sealed, such that the volume of water drained out within two minutes. However, we
noticed that some points of connection were better sealed than others. The diameter of the base
was tightly connected with the cylinder; most of the leaking came through the connection points
between the dividers and the base.  

We plan to resolve this issue by better developing a seal system between the dividers and the
base. Specifically, we will purchase rubber flaps from McMaster to attach to the bottoms of the
dividers, sealing the gap and reducing leakage.

**3. Weight test** 

This test was performed to test the strength of our base, cylinder, and rotation system in
functioning under increased loads. It was performed by adding weights to the base in ~550g
increments, observing any physical deformation in our design, and rotating
the handle and making note of ease of rotation.  

The test provided valuable insight as to how our design functions under increased loads. First, we
noticed that as weight was added, the gap between the base and the dividers marginally increased,
lowering friction and making rotation occur more smoothly (but also implying increased water
leakage). Second, we noticed that if our design is used in such a way where only one out of three
sections is filled with mixture at a given time, this unevenly distributed weight will cause the base
to tilt down at an angle, greatly inhibiting water retention and structural integrity.   

Last, we noticed that the numeric limit to functionality of rotation of our cylinder fell at approximately 2.0 kg. Any weight beyond this caused greatly angled deflection of the base. These results have important design implications. The first observation, regarding the widening
gap between the dividers and the base, indicated that a support system beneath the base is quite
necessary — the shaft collar and press fit between the shaft and base is not sufficient to vertically
support the load. This was not a surprise or concern, as our design already accounts for placing
bolts under the base — we were just not able to incorporate them into this prototype due to
tolerancing issues. The second observation will ideally also be resolved
by this solution, as the vertical support provided by the bolts will prevent the observed angled
deflection. However, we also plan to explore optimizing our design so that two out of three
sections can be filled and filtered simultaneously — which would not only increase efficiency, but
help limit the observed angled deflection due to more even distribution of loading.





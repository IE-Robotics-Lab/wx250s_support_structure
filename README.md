# WX250_support_structure
Design a robust base and modular rest position for the Widow X 250 Trossenrobotics robotic arm to facilitate the creation of a visually striking Robot Garden. The primary goals are to ensure ease of handling and movement of the robot arm while maintaining security and enhancing visual impact.

by [Gregorio Orlando](https://github.com/GRINGOLOCO7)

## Table of Contents
- [Objective & Scope](#objective--scope)
- [Key Objectives](#key-bjectives)
- [Features](#features)
  - [Base](#base)
  - [Support Trees](#support-trees)
- [Solution](#solution)
  - [Base](#base-1)
  - [Support Trees](#support-trees-1)
- [Outcome](#outcome)
  - [Design & Aesthetics](#design--aesthetics)
  - [Ease of Use for Students](#ease-of-use-for-students)
  - [Hassle-free Electronics](#hassle-free-electronics)
  - [Modular Rest Position](#modular-rest-position)
  - [Educational Value](#educational-value)
- [Conclusion](#conclusion)
  - [Achievements](#achievements)
  - [Next Steps](#next-steps)
  - [Future Enhancements](#future-enhancements)


## Objective & Scope

The goal is to design a **sturdy support system** for the [Widow X 250](https://docs.trossenrobotics.com/interbotix_xsarms_docs/specifications/wx250.html) Trossenrobotics robot arm series. This support system should offer:

- A **stable and modular rest position** for the robotic arm.
- A **compact and durable base** that securely houses all electronics, cables, and a Raspberry Pi.
- Flexibility to accommodate a **counterweight** of 1 or 2 lbs or a **screw gripper** to maintain the arm's stability during movement.

## Key Objectives:

- Robust Base: Develop a stable and durable base that securely houses the Widow X 250 Trossenrobotics robotic arm and its accompanying electronics.
- Modular Rest Position: Create a modular rest position system that allows for easy adjustment and customization of the robot arm's resting configuration. This system should offer flexibility in arrangement to accommodate different spatial constraints and user preferences.
- Ease of Handling: Ensure that the robot arm can be easily grabbed and moved with minimal effort, providing users with a seamless and intuitive experience.
- Visual Impact: Enhance the visual appeal of the Robot Garden by designing the base and rest position components to be aesthetically pleasing and visually striking.
<br>

## Features

### Base:
- **Electronics Management:** Securely contain all electronics, cables, and Raspberry Pi within the base.
- **Attachment:** Easily attachable to the robot arm's base.
- **Stability:** Incorporate a 1 or 2 lb [counterweight](https://www.amazon.co.uk/HFS-Chrome-Scale-Calibration-Weight/dp/B09SB4KM4X/ref=sr_1_1_sspa?crid=2H128576C3IBV&dib=eyJ2IjoiMSJ9.h9-fcQ-6N_kG1OWeTmowNHWuDgPQd7Ymil7JAZnOfCqof-iIMCpy5fOzPmx4_2KbHe8HbSlJBLhSjHj0Sp1OlTHo1yOxeHQP8zM7_j96UEjnYd-qD-qR5-j-v7zyEks0bU-CyXxOgn2OSU7J1Oeu5CguVItciMbkkwVLvyv54-mcV1D07bfBtU5H2AGA2q3EFGL-dnX5zpP7-lGN5k8NBf7uCUjMamdYIqSg0tYzF6y7itpMemrdZoT3YCGckmecynkeVtoQ40xVWsisu5M5Cd3QEQIasI2ngmPGuxhMDYU.TWPBXmscEAjVQNwlfdmpMiqPIZ0pkW5_VJs6ZfOLynM&dib_tag=se&keywords=1kg%2Bweight&qid=1713354838&sprefix=1kg%2Bw%2Caps%2C206&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1) or a [screw gripper](https://www.amazon.es/WORKPRO-Sargento-Abrazadera-Liberaci%C3%B3n-Carpinter%C3%ADa/dp/B0932WDQ9Z/ref=sr_1_2_sspa?__mk_es_ES=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=11W6SGH33MCVY&dib=eyJ2IjoiMSJ9.wKmDEqxE875TI0Df4FY2ZVLFTZsGsYukTiMmVJs1cdiYxioKiMrd23C6xTyS4MOZWLSzHdAtMDGgWAl1aXw5YTFHlxgzn2sMkW5ZoXIBxnWtO_Tqya4Lh76k4vk9Dnw-ErXnXyx0BG_t0uVOoBslfolrhHsrqkHz_eK_Buy0f_hzRy9lupvHdO0eyeKfEYconaPYDHQ2tAtV9PhuiM9CuTzv617Kg3cmJE6GTH1etlJbMM2VTk6pFg3aQqDdXEbvYhFcx38qjj4WgxCNZOOAJZCSsiwwUcknZrpQKL_bG90.n1stWsBlwqh9XijcYghF5-QhjvMvBxIL-8ZatFclHBY&dib_tag=se&keywords=sargento+de+tornillo&qid=1714052680&sprefix=sargento+de+tornillo+%2Caps%2C157&sr=8-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1) to maintain stability during movement.

<br>

### Support Trees:
- These must provide a solution for creating a robot garden. The rest position must be modular, allowing for various combinations of rest positions.
- Each module must securely attach to the Trossen arm and provide stability to the configuration.

<br>

## Solution

### Base:
We have devised a method to consolidate all electronics into a compact and secure space. Our approach is greatly inspired by the detailed [Trossen Robotics CAD documentation](https://docs.trossenrobotics.com/interbotix_xsarms_docs/specifications/wx250.html).

Key Features:
- **CAD-Inspired Design:** Utilizing the CAD design provided by Trossen Robotics, we customized the base to meet our specific requirements.
- **Compact Electronics Box:** We've redesigned the electronic housing to ensure freedom of movement for the 6DoF arm, minimizing any potential self-collisions.
- **Integrated Support Mounts:** The supports for the electronics are built-in components, enhancing stability and structural integrity.
- **Raspberry Pi Mounting Wall:** A dedicated wall has been designed to securely mount the Raspberry Pi case.
- **Cable Management "Tentacles":** Specialized channels have been incorporated to guide and organize cables, ensuring a tidy setup.

<div align="center">
  <div style="display: inline-block; margin-right: 20px;">
    <img src="/images_and_videos/base_frontview.jpg" alt="Support Tree Front View" width="200" />
  </div>
  <div style="display: inline-block; margin-right: 20px;">
    <img src="/images_and_videos/base_lateralview.jpg" alt="Support Tree Side View" width="200" />
  </div>
  <div style="display: inline-block;">
    <img src="/images_and_videos/base_sideview.jpg" alt="Third Image" width="200" />
  </div>
</div>


<br>

### Support Trees:
Upon measuring the dimensions of the Trossen "bones" of the robot arm, we've crafted Lego-style support trees. These modular support structures allow for easy assembly and customization, enhancing stability and flexibility in the configuration.


<div align="center">
  <div style="display: inline-block; margin-right: 20px;">
    <img src="/images_and_videos/support_tree_frontview.jpg" alt="Support Tree Front View" width="200" />
  </div>
  <div style="display: inline-block;">
    <img src="/images_and_videos/support_tree_sideview.jpg" alt="Support Tree Side View" width="200" />
  </div>
</div>


<br>

## Outcome

The result of our efforts is a beautifully designed, visually appealing, and highly functional robot garden.

### Design & Aesthetics:
The design showcases a harmonious blend of form and function. With its sleek and modern appearance, the robot garden is not only a functional tool but also a captivating piece of technology that draws attention.

### Ease of Use for Students:
Designed with students in mind, the robot garden offers ease of access and portability. Students can simply arrive in class, grab a robot from the base or tree, and place it on their desks to start working. This seamless transition from the base to the desk promotes an interactive learning experience.

### Hassle-free Electronics:
We've prioritized user-friendly features to ensure that Raspberry Pi, electronics, and cables are not obstacles for the users. By leveraging SSH capabilities, users can easily connect to the Raspberry Pi for development without worrying about complex setups or cable management issues.

### Modular Rest Position:
The modular rest position design of the robot garden provides flexibility in configurations. Whether it's for storage, display, or working mode, the rest position can be easily adjusted to suit various needs, offering both stability and adaptability.

### Educational Value:
Beyond its functional aspects, the robot garden serves as an educational platform. It encourages hands-on learning, fosters creativity, and promotes collaborative problem-solving among students.

<br>

<div align="center">
  <div style="display: inline-block; margin-right: 20px;">
    <img src="/images_and_videos/robot_composition_final_outcome.jpg" alt="Support Tree Front View" width="200" />
  </div>
  <div style="display: inline-block;">
    <img src="/images_and_videos/robot_composition_final_outcome2.jpg" alt="Support Tree Side View" width="200" />
  </div>
</div>


<div align="center">
  <div style="text-align:center;">
    <video width="640" height="360" controls style="margin:auto;">
      <source src="/images_and_videos/final_product_poc.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
</div>
<br>

<div align="center">
  <div style="text-align:center;">
    <div style="display: inline-block;">
      <img src="/images_and_videos/robots_composition.jpg" alt="Third Image" width="300" />
    </div>
  </div>
</div>


## Conclusion

In conclusion, the task is successfully completed, and the robots are ready for setup.

### Achievements:
- **Design Excellence:** We've achieved a harmonious blend of aesthetics and functionality with our beautifully designed robot garden.

- **User-Friendly Experience:** The design prioritizes ease of use, allowing students to effortlessly grab a robot from the base or tree and start working.

- **Seamless Integration:** With hassle-free electronics and SSH capabilities, the setup process is straightforward, making it easier for users to dive into development.

- **Modular Flexibility:** The modular rest position offers adaptability, allowing for various configurations to suit different needs.

### Next Steps:
With the robots ready, the next phase involves setting them up in the desired locations and initiating hands-on learning experiences. We look forward to seeing how these robots will contribute to interactive learning and collaborative projects.

### Future Enhancements:
While the current design meets the project requirements, there's always room for improvement and innovation. Future enhancements may include additional features, optimizations, or new modules to further enhance the robot garden's capabilities.

Thank you to everyone involved in making this project a success. We're excited about the potential of these robots and the educational opportunities they offer.

<br>
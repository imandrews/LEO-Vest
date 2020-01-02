### What is the LEO Vest Project?
The LEO (Low-Vision Optoelectronic) Vest is a wearable device that seeks to use sensory substitution to improve user function for those with peripheral vision impairment. The goal of this project is to provide an option for patients who suffer from reduced vision by enhancing their peripheral field of vision, as currently most medical treatment techniques focus on restoring or supplementing central vision. The device is intended be a portable, wearable system with a camera and computer that parses information from the camera and transmits the information as vibrations on the patient's skin to help them identify the location of objects outside their field of view. This project is inspired by an Intel project called IRSAW (Intel RealSense Spatial Awareness Wearable) which is no longer being pursued by Intel. This device will ideally be more ergonomically patient friendly and implemented in such a way that more users will be able to benefit from this product.

### Current Stage of Development
Testing. As few studies have been done in this area, our goal is first and foremost to develop a stable system so we can proceed with clinical trials. We need to know how valid sensory substitution is for patients before we begin trying to fine tune the device. Once we have this data we will then start to look for areas of improvement or, if results were negative, look for a way to better address the problem.

### How Does it Work?
The device consist of a small computer​ and battery (both roughly the size of a smart phone) along with a depth sensing camera all attached to a belt. The IRSAW program which runs on the computer takes input from the camera and processes it in real time. We break the view of the camera up into eight regions (the exact optimal number of regions has yet to be determined) and in each region we take look at the value of the closest pixel and assign the whole region to that value. Along with the belt the user is also wearing a vest with eight actuator boxes (six on the torso and two on the ankle). The boxes consist of a small battery, power switch, vibration motor and micro controller with wireless capabilities. Each box corresponds to a region of the camera, and after that closest pixel value is detected the main program on the computer sends a signal to each box to have them vibrate their motor at a certain value. Harder vibrations mean that the object in view is closer. This all happens dynamically and so a person with a reduced field of vision wearing this device could walk around receive feedback about stimuli in their area and thus better redirect their limited vision to process it.

### What resources are Availible on this GitHub?
This GitHub contains many resources for the LEO Vest and related projects. We have done and are doing experiments on the side to collect data that supports the concept the LEO Vest is built on. You can find past published works, protocols and source code for these experiments in their respective files. As for the main project we have documentation along with source code for the many components of the project (main program, micro-controller, etc.).

### Contact Information
This project is being done at the Institute for Vision Research at the University of Iowa. Many people have contributed to make this possible but for the purpose of contacting someone if you have questions or concerns please see one of the following below:

- Ian Andrews (ian-andrews@uiowa.edu)
- Nicole Tatro (ntatro@ivr.uiowa.edu)
- Dr. Steve Russell (steve-russell@uiowa.edu)
- Dr. Terry Braun (terry-braun@uiowa.edu)

# Automotive_Genesis_Oct22_team4

## Day1_activity_1

## Electronic control unit
An electronic control unit (ECU), also known as an electronic control module (ECM), is an embedded system in automotive electronics that controls one or more of the electrical systems or subsystems in a car or other motor vehicle.

Modern vehicles have many ECUs, and these can include some or all of the following: engine control module (ECM), powertrain control module (PCM), transmission control module (TCM), brake control module (BCM or EBCM), central control module (CCM), central timing module (CTM), general electronic module (GEM), body control module (BCM), and suspension control module (SCM). These ECUs together are sometimes referred to collectively as the car's computer though technically they are all separate computers, not a single one. Sometimes an assembly incorporates several individual control modules (a PCM often controls both the engine and the transmission). 
Some modern motor vehicles have up to 150 ECUs. Embedded software in ECUs continues to increase in line count, complexity, and sophistication. Managing the increasing complexity and number of ECUs in a vehicle has become a key challenge for original equipment manufacturers (OEMs).

# Engine control unit (ECU)
An engine control unit (ECU), also commonly called an engine control module (ECM), is a type of electronic control unit that controls a series of actuators on an internal combustion engine to ensure optimal engine performance. It does this by reading values from a multitude of sensors within the engine bay, interpreting the data using multidimensional performance maps (called lookup tables), and adjusting the engine actuators. Before ECUs, air–fuel mixture, ignition timing, and idle speed were mechanically set and dynamically controlled by mechanical and pneumatic means.
If the ECU has control over the fuel lines, then it is referred to as an electronic engine management system (EEMS). The fuel injection system has the major role of controlling the engine's fuel supply. The whole mechanism of the EEMS is controlled by a stack of sensors and actuators.
![ECU](https://user-images.githubusercontent.com/115522470/198248367-9ad31cba-07ee-41d8-9f33-4f54f793dd89.jpg)
 
# Workings
# Control of air–fuel ratio
Most modern engines use some type of fuel injection to deliver fuel to the cylinders. The ECU determines the amount of fuel to inject based on a number of sensor readings. Oxygen sensors tell the ECU whether the engine is running rich (too much fuel or too little oxygen) or running lean (too much oxygen or too little fuel) as compared to ideal conditions (known as stoichiometric). The throttle position sensor tells the ECU how far the throttle plate is opened when the accelerator (gas pedal) is pressed down. The mass air flow sensor measures the amount of air flowing into the engine through the throttle plate. The engine coolant temperature sensor measures whether the engine is warmed up or cool. If the engine is still cool, additional fuel will be injected.
Air–fuel mixture control of carburettors with computers is designed with a similar principle, but a mixture control solenoid or stepper motor is incorporated in the float bowl of the carburettor.
# Control of idle speed
Most engine systems have idle speed control built into the ECU. The engine RPM is monitored by the crankshaft position sensor, which plays a primary role in the engine timing functions for fuel injection, spark events, and valve timing. Idle speed is controlled by a programmable throttle stop or an idle air bypass control stepper motor. Early carburettor-based systems used a programmable throttle stop using a bidirectional DC motor. Early throttle body injection (TBI) systems used an idle air control stepper motor. Effective idle speed control must anticipate the engine load at idle.
A full authority throttle control system may be used to control idle speed and provide cruise control functions and top-speed limitation. It also monitors the ECU section for reliability.
# Control of variable valve timing
Some engines have variable valve timing. In such an engine, the ECU controls the time in the engine cycle at which the valves open. The valves are usually opened sooner at higher speed than at lower speed. This can increase the flow of air into the cylinder, increasing power and fuel economy.
# Electronic valve control
Experimental engines have been made and tested that have no camshaft, but have full electronic control of the intake and exhaust valve opening, valve closing, and area of the valve opening. Such engines can be started and run without a starter motor for certain multi-cylinder engines equipped with precision-timed electronic ignition and fuel injection. Such a static-start engine would provide the efficiency and pollution-reduction improvements of a mild hybrid-electric drive, but without the expense and complexity of an oversized starter motor. 

The first production engine of this type was invented (in 2002) and introduced (in 2009) by Italian automaker Fiat in the Alfa Romeo MiTo. Their Multiair engines use electronic valve control, which dramatically improves torque and horsepower while reducing fuel consumption as much as 15%. Basically, the valves are opened by hydraulic pumps, which are operated by the ECU. The valves can open several times per intake stroke, based on engine load. The ECU then decides how much fuel should be injected to optimize combustion.

At steady load conditions, the valve opens, fuel is injected, and the valve closes. Under a sudden increase in throttle, the valve opens in the same intake stroke and a greater amount of fuel is injected. This allows immediate acceleration. For the next stroke, the ECU calculates the engine load at the new, higher RPM and decides how to open the valve: early or late, wide-open, or half-open. The optimal opening and timing are always reached and combustion is as precise as possible. This is impossible with a normal camshaft, of course, which opens the valve for the whole intake period and always to full lift.
The elimination of cams, lifters, rockers, and timing set reduces not only weight and bulk, but also friction. A significant portion of the power that an engine actually produces is used up just driving the valve train, compressing all those valve springs thousands of times a minute.

Once more fully developed, electronic valve operation will yield even more benefits. Cylinder deactivation, for instance, could be made much more fuel efficient if the intake valve could be opened on every downstroke and the exhaust valve opened on every upstroke of the deactivated cylinder or "dead hole". Another even more significant advancement will be the elimination of the conventional throttle. When a car is run at part throttle, this interruption in the airflow causes excess vacuum, which causes the engine to use up valuable energy acting as a vacuum pump. BMW attempted to get around this on their V-10 powered M5, which had individual throttle butterflies for each cylinder, placed just before the intake valves. With electronic valve operation, it will be possible to control engine speed by regulating valve lift. At part throttle, when less air and gas are needed, the valve lift would not be as great. Full throttle is achieved when the gas pedal is depressed, sending an electronic signal to the ECU, which in turn regulates the lift of each valve event, and opens it all the way up.
# Powertrain control module
A power-train control module, abbreviated PCM, is an automotive component, a control unit, used on motor vehicles. It is generally a combined controller consisting of the engine control unit (ECU) and the transmission control unit (TCU). On some cars, such as many Chryslers, there are multiple computers: the PCM, the TCU, and the Body Control Module (BCM), for a total of three separate computers. These automotive computers are generally very reliable. The PCM commonly controls more than 100 factors in a car or truck. There are many hundreds of error codes that can occur, which indicates that some subsection of the car is experiencing a problem. When one of these errors occurs, usually it will turn on the "check engine" light on the dashboard. The PCM is one of potentially several on-board computers, or essentially the "brain" of the engine control system. 

The primary inputs to the PCM come from many sensors, of different types, that are spread around the car. Most of them are oriented toward engine management and performance. These sensors fail at a much higher rate than any of the computers do.
Early use of the powertrain control module dates back to the late 1970s - official phasing in of the PCM occurred during the early 1980s when used in conjunction with electronic controlled carburetors and lockup torque converters (at the time conventional 3-speed automatics received lockup converters at the same time overdrives were introduced.
 
# Transmission control unit
A transmission control unit (TCU), also known as a transmission control module (TCM), or a gearbox control unit (GCU), is a type of automotive ECU that is used to control electronic automatic transmissions. Similar systems are used in conjunction with various semi-automatic transmissions, purely for clutch automation and actuation. A TCU in a modern automatic transmission generally uses sensors from the vehicle, as well as data provided by the engine control unit (ECU), to calculate how and when to change gears in the vehicle for optimum performance, fuel economy and shift quality. 
Body control module

In automotive electronics, body control module or 'body computer' is a generic term for an electronic control unit responsible for monitoring and controlling various electronic accessories in a vehicle's body. Typically in a car the BCM controls the power windows, power mirrors, air conditioning, immobilizer system, central locking, etc. The BCM communicates with other on-board computers via the car's vehicle bus, and its main application is controlling load drivers – actuating relays that in turn perform actions in the vehicle such as locking the doors, flashing the turn signals (in older cars), or dimming the interior lighting.




## Day1_activity_2

# Brake system in car	

Braking systems in passenger vehicles use two primary types of brakes: disc brakes and drum brakes . While they both bring a vehicle to a stop, they differ in design and operation. Disc brakes are the only type used in the front of vehicles but may be found at all four wheels.

# Functions of the automotive braking system

Below are the functions braking system used in the automotive engine:
•	A brake system helps to stop vehicles within the smallest possible distance. This is achieved by converting the kinetic energy of the vehicle into heat energy.
•	It also functions on a mechanical device where motion occurs, the brake is applied to stop it within a short period of time.
![autmatic brake system](https://user-images.githubusercontent.com/115522470/198206997-a79a78d6-51b4-4059-a27a-29a4df110655.jpg)

# Components of the braking system

Below are the components used in the automotive braking system:

Brake pedal: the component of a brake system is used to activate the brake by pressing it down by foot. It’s located in the middle of the accelerator and clutch pedal inside the vehicle.

Fluid reservoir: The fluid reservoir is the housing where the brake fluid or brake oil is store.

Fluid lines: The fluid lines are the pipes through which the brake fluid flows in the vehicle.

Brake pads: The brake pad is a steel backing plate employed on disc brakes. It’s often made of ceramic, metal, or other hard-wearing composite materials.

Brake shoes: Brake shoes are two pieces of sheet steel joined together so it can carry the brake lining.

Brake drum: The brake drum is a rotating drum-shaped component used in the drum brake system.

Rotor: The rotor is a cast-iron brake disc connected to a wheel or axle, sometimes made of reinforced carbon-carbon, ceramic matric, or some other composite.

Brake lining: A brake lining is a heat-resistant, soft but also tough material with high friction characteristics. It’s enclosed inside the brake shoe.

Caliper: The caliper carries the brake pads and pistons.

Floating caliper or sliding caliper: the part moves relatively with the rotor as it uses a piston on a single side of the disc to push the inner brake pad into the 
braking surface. It then pulls the caliper body in to apply pressure on the opposite side of the disc.

Fixed calipers: the fixed caliper does not move in relative to the rotor, which works sensitive to imperfections. It uses one or more single pairs of opposing pistons to clamp from each side of the rotor.

Master cylinder: the master cylinder converts the non-hydraulic pressure from the driver’s foot into hydraulic pressure. it then controls the slave cylinders at the opposite end of the hydraulic system.

Vacuum booster: this braking system component is used to improve the master cylinder and increase pressure to which the driver foot supply through the use of a vacuum in the engine intake. This is effective while the vehicle’s engine is running.

# Brake Systems of the Future

Brake systems are becoming increasingly intelligent so they can meet the future needs and requirements of automated driving and electrification; and this in newly conceived vehicles designed with modified architecture. This functional extension requires a profound understanding of the system in order to combine uncompromising safety and sustainability in future brake systems – and in the long term also modular and distributed brake systems.

# The future began in 2016, and is now reality on the road

The first electrohydraulic brake-by-wireMK C1 brake system developed by Continental went into production back in 2016. It takes up less installation space, consists of fewer components, is lighter and, most importantly, thanks to electromechanical actuation, it builds up brake pressure faster than any conventional hydraulic system – in just 150 ms. This brake system does not require any brake booster and also no longer requires a vacuum pump. This FBS stage (FBS 0) marks the entry into brake-by-wire systems. By decoupling the brake pedal from the physical actuation system, body force is no longer required for effective emergency braking. Unlike systems with a brake booster, dosage of the maximum braking power does not depend on the force in the foot as with the MK C1, meaning that even those who are physically untrained can effortlessly initiate full braking.

But the MK C1 also achieves something else: In vehicles powered by electric motors, when pressing the brake pedal, the driver cannot tell whether the wheel brake is active, or whether the electric motor is operating regeneratively and decelerating the vehicle as desired while generating electricity in the process (recuperation). The pedal always feels the same because the pedal response (i.e. “pedal feel”) is constantly simulated. Intelligent brake systems do not necessarily do what drivers directly request, but rather what they intend to do: deceleration. This constitutes a major advance in vehicle efficiency that “burns” as little of the vehicle’s kinetic energy as possible on the wheel brakes, as this energy is then lost. Starting with the MK C1, the energy recuperation potential can be fully exploited. With an additional module based on the tried-and-tested ESC technology, automated driving according to SAE Level 3 is also possible. 

For this purpose, all that needs to be adjusted with the MK C1 is the functional scope of the software, which results in very low integration outlay on the part of automotive manufacturers. In its first production application, the MK C1 system from 2016 still has what is known as a “hydraulic fallback mode”: If a fault occurs (such as complete failure of the onboard electrical system), two valves automatically switch and the driver’s foot pressure generates brake pressure. However, the MK C1 can be used just as well without the hydraulic fallback mode.

# FBS 1 – True brake-by-wire technology
Building on the long experience gained with tried-and-tested electromechanical actuation, the transition to a complete brake-by-wire system can now follow. To this end, Continental has developed the MK C2, a modularized and scalable system generation. The MK C2 can be used both with a mechanical pedal (= and hydraulic fallback mode) as well as with an electronic pedal (= without fallback mode, as the MK C2 EP version).

The MK C2, as a more advanced development, is even more compact, lighter and more cost-effective and, thanks to Multi-Logic, has performance characteristics superior to those of the MK C1. Multi-Logic means that the MK C2 features two printed circuit boards and two processors that can be used to uphold more functions in the event of a fault. This means, for example, that the parking brake can be actuated redundantly. This makes it possible to dispense with a highly expensive mechanical transmission lock for immobilizing the vehicle. Owing to its benefits, the MK C2 evolutionary stage will form the basis for future FBS. 

In the version without fallback mode, the driver depresses a simulated brake pedal (electronic pedal feature). Sensors capture the braking intent, and an electric motor generates the hydraulic pressure. The MK C2 system generation is designed for AD in accordance with SAE Level 3 or higher. Since it is a requirement that brake systems without hydraulic fallback mode must be designed redundantly, FBS 1.1 is a smart solution suitable for small to medium unit volumes. It uses existing components that have already proven themselves in the solution with a mechanical pedal for higly automated driving (HAD). For larger unit volumes, the development of a redundant “OneBox” presents a good solution.

The complete separation of pedal and pressure generation without fallback mode provides a huge advantage for integration, which is characteristic of real brake-by-wire systems: The brake system no longer has to be mounted directly at a specific location on the firewall in front of the driver to enable mechanical fallback. Instead, an FBS 1 with electronic pedal supports new vehicle concepts involving different vehicle interiors and dimensions, such as the skateboard chassis of electrified vehicles, on which various bodies can be mounted.
 
 ![MKC2](https://user-images.githubusercontent.com/115522470/198206464-b0217e32-73a8-437e-bc0b-67afdf0bcb54.jpg)
                         The MK C2 is compact and lightweight, powerful, and still highly cost-optimized.

#FBS 2 – The brakes become “semi-dry”
In today’s brake systems, as well as with FBS 0 and FBS 1 solutions, pressure generation is still fully integrated into the brake system unit. The hydraulics (i.e. the “wet” part of the brake system) transmit the force to the brake calipers of the disk brakes or the drum brakes.

The more E/E architecture and vehicle architecture evolve, the more attractive it becomes to eliminate this inflexible “one-box arrangement”. A first step, for example, could be to no longer actuate the brakes hydraulically on the rear axle, because hydraulics have a disadvantage: The fluid has to be changed and disposed of regularly – which is not environmentally sustainable. Moreover, if the brakes were actuated electromechanically, installation of the rear axle would be simplified because rigid hydraulic lines could be dispensed with. At the same time, the hydraulics on the front axle would still be available as a fallback system.

If the rear axle wheel brakes are operated electromechanically, i.e. “dry”, this could be utilized regeneratively, for example for systematic energy recuperation at the rear axle during each braking operation. Once the rear axle brakes become independent of the hydraulic system, they provide the ideal conditions for this. This would require a certain degree of “intelligence” in the brake system. This decentralization and “breaking-up” of the conventional architecture would further increase the degree of freedom for vehicle architectures.

# FBS 3 – The brake can be broken up into modules
In a very long-term view, the hydraulic system could be eliminated completely: To achieve this, all four wheel brakes could be actuated electromechanically and would thus be completely “dry”. The current focus on pressure generation and modulation with appropriate control intelligence would then no longer be necessary. An FBS 3 brake system consists of the four dry wheel brakes (calipers or drums) and a series of software function blocks which, for reasons of safety and redundancy, can run on several of the existing high-performance computers (HPC) with integrated Wheel Control Units providing the redundancy required for safety.
To make this long-term transformation to FBS 3 possible at all, the individual functions of a brake system must be encapsulated as stand-alone products in modular, validated and proven software blocks that can be integrated into various vehicles thanks to standardized interfaces based on the principle of re-use.

Video Resource: https://www.youtube.com/watch?v=W9ysHClUpQk

## Day1_activity_3
#Mercedes-AMG GLC 63 Coupe Becomes 700-HP Superweapon

	The Manhart GLR 700 is based on the Mercedes-AMG GLC 63 S Coupe that features a twin-turbo 4.0-liter V8 producing 503 hp and 516 lb-ft of torque.

	Power is sent to all four wheels via a nine-speed automatic transmission, resulting in a 0-60 mph time of 3.6 seconds and a top speed of 174 mph.

	Manhart ups the power output to an astonishing 707 hp and 668 lb-ft of torque by adding its own turbo performance kit which includes a set of larger turbos, a carbon air intake, a more efficient intercooler, and a transmission upgrade. 

	Gasses are passed through a stainless-steel sport exhaust system and free-flowing downpipes. 

	To keep all that power planted to the ground, Manhart also lowers the car by 1.2 inches and adds a set of 21-inch wheels wrapped in 295/35 ZR21 at the back, and 20-inch wheels at the front.

	Manhart offers numerous exterior styling options, and the one pictured here gets an in-your-face set of gold decals and gold highlights on the wheels, as well as a black radiator grille. 

	 The GLR 700 is customized with a specially crafted Manhart leather interior with individually chosen accents and an Alcantara headliner.

## Day1_activity_4

**Difference between Maruti Suzuki swift desire vs Nissan Terrono XV**

| **Sl No** | **Specification** | **Maruti Suzuki Dzire** | **Nissan Terrano** |
| --- | --- | --- | --- |
| 1 | Engine Type | 1.2-litre VVT Petrol 1,197 CC | 4 Cylinders In-Line 1,461 CC |
| 2 | Power | 89 bhp@6000 rpm | 108 bhp@3900 rpm |
| 3 | Torque | 113 Nm@4400 rpm | 248 Nm@2250 rpm |
|   | Dimension |
| 4 | Length | 3,995 mm | 4,331 mm |
|5  | Width | 1,735 mm | 1,822 mm |
| 6| Height | 1,515 mm | 1,671 mm |
|7 | Wheelbase | 2,450 mm | 2,673 mm |
|8 | Ground Clearance | 163 mm | 205 mm |
 |9 | Boot Space | 378 L | 475 L |
|10  | No. of gears | 5 | 6 |
| 11 | Wheel Type | Steel Wheels With Hub Cap | Alloy Wheel |
| 12 | Front Tyre Size | 165/80 R14 | 215/65 R16 |
| 13| Rear Tyre Size | 165/80 R14 | 215/65 R16 |
| 14| Front Suspension | MacPherson Strut | Independent McPhearson Strut With Coil Springs & Anti-Roll Bar |
| 15 | Rear Suspension | Torsion Beam | Torsion Beam Axle With Coil Springs & Anti-Roll Bar |
| 16 | Mileage | 22.00 KM/L | 19.64 KM/L |
| 17 | Fuel tank Capacity | 37.0 | 50 |
| 18 | Steering Type | Electric Power Steering | Electro-Hydraulic Power Steering |
| 19 | Airbags | 2 | 4 |
| 20 | Rear Parking Sensors | N0 | yes |
| 21 | ABS + EBD with Brake Assist | N0 | yes |
| 22 | Electrically Adjustable Rear View Mirror | N0 | yes |
| 23 | Height Adjustable Driver Seat | N0 | yes |
| 24 | Light Type | LED | Halogen |
| 25 | Front Fog Lamps | N0 | yes |
| 26 | Bluetooth Hands-Free Phone System | N0 | yes |
| 27 | Multi-Function Display | N0 | yes |

## Day2_activity_1
# Levels of Autonomous Driving

# Level 0 – No Driving Automation
Level 0 (zero) refers to a vehicle that has no driving automation technology. In this case, the driver is entirely in charge of operating the vehicle’s movement, including steering, accelerating, braking, parking, and any other necessary maneuver to move the car in any direction. 
However at Level 0, driver support systems that may temporarily intervene during driving may be present. Examples include stability control, forward-collision warning, automatic emergency braking, blind-spot warning, and lane-keeping assistance. These technologies are considered Level 0 because they do not drive the vehicle but offer alerts or momentary action in specific situations. The majority of vehicles on American roadways are Level 0.

# Level 1 Driving Automation – Driver Assistance
At Level 1, the lowest rung of automation, a vehicle has at least one driver support system that provides steering assistance OR braking and acceleration assistance. The driver remains responsible for driving the vehicle and must be prepared to take control at any time and for any reason.
Adaptive cruise control is an example of a Level 1 driver assistance technology. It maintains a safe following distance between your vehicle and traffic ahead without any intervention by the driver. A steering assistance feature, such as lane-centering assistance or lane-following assistance, would also qualify as Level 1 autonomy. 
However, a vehicle with both of these features working together qualifies as Level 2 driving automation.

# Level 2 Driving Automation – Partial Driving Automation
Level 2 driving automation applies to vehicles with advanced driving assistance systems (ADAS) that can take over steering, acceleration, and braking in specific scenarios. But, even though Level 2 driver support can control these primary driving tasks, the driver must remain alert and is required to actively supervise the technology at all times.

An example of Level 2 driving automation is Highway Driving Assist, installed in Genesis, Hyundai, and Kia vehicles. It requires the driver to have her hands on the steering wheel but actively steers, accelerates, and brakes the vehicle when traveling on highways. BlueCruise is a new hands-free partial driving automation technology from Ford. It is more sophisticated than Highway Driving Assist, allowing the driver to take her hands off of the steering wheel on specific, approved highways in the U.S. and Canada.

Both of these examples of Level 2 driving automation require the driver to remain alert, engaged, and ready to take control at any time. For the record, and according to what the automaker told the state of California, Tesla’s new Full Self Driving Capability technology is a Level 2 system, and it will remain so when Autosteer for city streets arrives as an over-the-air software update.

# Level 3 Driving Automation – Conditional Driving Automation

![levels of driving automation](https://user-images.githubusercontent.com/115522470/198267491-65a568c3-61c0-47af-aa50-4ff4b7721941.jpg)

Level 3 is known as conditional driving automation. It uses various driver assistance systems and artificial intelligence to make decisions based on changing driving situations around the vehicle. People inside the vehicle do not need to supervise the technology, which means they can engage in other activities. However, a human driver must be present, alert, and able to take control of the vehicle at any time, especially in the case of an emergency due to system failure.
Audi developed a Level 3 traffic jam assistance technology for its 2019 A8 flagship sedan, but it never received regulatory approval for the system in Germany and has since shelved the effort. That opened the door for Honda to become the first automaker in the world to sell an approved Level 3 traffic jam assistance system to consumers. It went on sale as an upgrade to the company’s Legend flagship sedan in early 2021, offered in low quantities and only for use in the automaker’s home market of Japan.

Other vehicles equipped with Level 3 driving automation but waiting for regulatory approval include the redesigned 2021 Mercedes-Benz S-Class and the all-new 2022 Mercedes-Benz EQS electric vehicle. The Mercedes technology is called Drive Pilot.

# Level 4 Driving Automation – High Driving Automation
Referred to as high-driving automation, Level 4 autonomy does not require any human interaction in the vehicle’s operation because it is programmed to stop itself in the event of system failure. Since a human driver is never needed, a Level 4 vehicle may not have a steering wheel and pedals.
Level 4 driving automation technology is for use in driverless taxis and public transportation services. Such vehicles will be programmed to travel between Point A and Point B and restricted to specific geographic boundaries by geofencing technology. Certain conditions may limit or cancel Level 4 autonomous vehicle operation, such as severe weather.

# Level 5 Driving Automation – Full Driving Automation
As the highest classification of driving automation, Level 5 means a vehicle can drive itself everywhere in all conditions without any human interaction. A Level 5 vehicle is neither bound by geofencing nor affected by weather and transports human beings comfortably and efficiently without requiring a driver. The only human involvement will be to set a destination


## Day2_activity_2
# Software Development Life Cycle (SDLC)
# Overview

Software Development Life Cycle (SDLC) is a process used by the software industry to design, develop and test high quality softwares. The SDLC aims to produce a high-quality software that meets or exceeds customer expectations, reaches completion within times and cost estimates.

•	SDLC is the acronym of Software Development Life Cycle.

•	It is also called as Software Development Process.

•	SDLC is a framework defining tasks performed at each step in the software development process.

•	ISO/IEC 12207 is an international standard for software life-cycle processes. It aims to be the standard that defines all the tasks required for developing and maintaining software.

# What is SDLC
SDLC is a process followed for a software project, within a software organization. It consists of a detailed plan describing how to develop, maintain, replace and alter or enhance specific software. The life cycle defines a methodology for improving the quality of software and the overall development process.
The following figure is a graphical representation of the various stages of a typical SDLC.
 
A typical Software Development Life Cycle consists of the following stages −
# Stage 1: Planning and Requirement Analysis
Requirement analysis is the most important and fundamental stage in SDLC. It is performed by the senior members of the team with inputs from the customer, the sales department, market surveys and domain experts in the industry. This information is then used to plan the basic project approach and to conduct product feasibility study in the economical, operational and technical areas.
Planning for the quality assurance requirements and identification of the risks associated with the project is also done in the planning stage. The outcome of the technical feasibility study is to define the various technical approaches that can be followed to implement the project successfully with minimum risks.
# Stage 2: Defining Requirements
Once the requirement analysis is done the next step is to clearly define and document the product requirements and get them approved from the customer or the market analysts. This is done through an SRS (Software Requirement Specification) document which consists of all the product requirements to be designed and developed during the project life cycle.
# Stage 3: Designing the Product Architecture
SRS is the reference for product architects to come out with the best architecture for the product to be developed. Based on the requirements specified in SRS, usually more than one design approach for the product architecture is proposed and documented in a DDS - Design Document Specification.
This DDS is reviewed by all the important stakeholders and based on various parameters as risk assessment, product robustness, design modularity, budget and time constraints, the best design approach is selected for the product.
A design approach clearly defines all the architectural modules of the product along with its communication and data flow representation with the external and third party modules (if any). The internal design of all the modules of the proposed architecture should be clearly defined with the minutest of the details in DDS.
# Stage 4: Building or Developing the Product
In this stage of SDLC the actual development starts and the product is built. The programming code is generated as per DDS during this stage. If the design is performed in a detailed and organized manner, code generation can be accomplished without much hassle.
Developers must follow the coding guidelines defined by their organization and programming tools like compilers, interpreters, debuggers, etc. are used to generate the code. Different high level programming languages such as C, C++, Pascal, Java and PHP are used for coding. The programming language is chosen with respect to the type of software being developed.
# Stage 5: Testing the Product
This stage is usually a subset of all the stages as in the modern SDLC models, the testing activities are mostly involved in all the stages of SDLC. However, this stage refers to the testing only stage of the product where product defects are reported, tracked, fixed and retested, until the product reaches the quality standards defined in the SRS.
# Stage 6: Deployment in the Market and Maintenance
Once the product is tested and ready to be deployed it is released formally in the appropriate market. Sometimes product deployment happens in stages as per the business strategy of that organization. The product may first be released in a limited segment and tested in the real business environment (UAT- User acceptance testing).
Then based on the feedback, the product may be released as it is or with suggested enhancements in the targeting market segment. After the product is released in the market, its maintenance is done for the existing customer base.

# SDLC Models
There are various software development life cycle models defined and designed which are followed during the software development process. These models are also referred as Software Development Process Models". Each process model follows a Series of steps unique to its type to ensure success in the process of software development.

Following are the most important and popular SDLC models followed in the industry −
•	Waterfall Model

•	Iterative Model

•	Spiral Model

•	V-Model

•	Big Bang Model

Other related methodologies are Agile Model, RAD Model, Rapid Application Development and Prototyping Models.

# SDLC - Waterfall Model
The Waterfall Model was the first Process Model to be introduced. It is also referred to as a linear-sequential life cycle model. It is very simple to understand and use. In a waterfall model, each phase must be completed before the next phase can begin and there is no overlapping in the phases.
The Waterfall model is the earliest SDLC approach that was used for software development.
The waterfall Model illustrates the software development process in a linear sequential flow. This means that any phase in the development process begins only if the previous phase is complete. In this waterfall model, the phases do not overlap.

# Waterfall Model - Design
Waterfall approach was first SDLC Model to be used widely in Software Engineering to ensure success of the project. In "The Waterfall" approach, the whole process of software development is divided into separate phases. In this Waterfall model, typically, the outcome of one phase acts as the input for the next phase sequentially.
The following illustration is a representation of the different phases of the Waterfall Model.
 
The sequential phases in Waterfall model are −

•	Requirement Gathering and analysis − All possible requirements of the system to be developed are captured in this phase and documented in a requirement specification document.

•	System Design − The requirement specifications from first phase are studied in this phase and the system design is prepared. This system design helps in specifying hardware and system requirements and helps in defining the overall system architecture.

•	Implementation − With inputs from the system design, the system is first developed in small programs called units, which are integrated in the next phase. Each unit is developed and tested for its functionality, which is referred to as Unit Testing.

•	Integration and Testing − All the units developed in the implementation phase are integrated into a system after testing of each unit. Post integration the entire system is tested for any faults and failures.

•	Deployment of system − Once the functional and non-functional testing is done; the product is deployed in the customer environment or released into the market.

•	Maintenance − There are some issues which come up in the client environment. To fix those issues, patches are released. Also to enhance the product some better versions are released. Maintenance is done to deliver these changes in the customer environment.

All these phases are cascaded to each other in which progress is seen as flowing steadily downwards (like a waterfall) through the phases. The next phase is started only after the defined set of goals are achieved for previous phase and it is signed off, so the name "Waterfall Model". In this model, phases do not overlap.

# Waterfall Model - Application
Every software developed is different and requires a suitable SDLC approach to be followed based on the internal and external factors. Some situations where the use of Waterfall model is most appropriate are −

•	Requirements are very well documented, clear and fixed.

•	Product definition is stable.

•	Technology is understood and is not dynamic.

•	There are no ambiguous requirements.

•	Ample resources with required expertise are available to support the product.

•	The project is short.

# Waterfall Model - Advantages
The advantages of waterfall development are that it allows for departmentalization and control. A schedule can be set with deadlines for each stage of development and a product can proceed through the development process model phases one by one.
Development moves from concept, through design, implementation, testing, installation, troubleshooting, and ends up at operation and maintenance. Each phase of development proceeds in strict order.

Some of the major advantages of the Waterfall Model are as follows −

•	Simple and easy to understand and use

•	Easy to manage due to the rigidity of the model. Each phase has specific deliverables and a review process.

•	Phases are processed and completed one at a time.

•	Works well for smaller projects where requirements are very well understood.

•	Clearly defined stages.

•	Well understood milestones.

•	Easy to arrange tasks.

•	Process and results are well documented.

# Waterfall Model - Disadvantages

The disadvantage of waterfall development is that it does not allow much reflection or revision. Once an application is in the testing stage, it is very difficult to go back and change something that was not well-documented or thought upon in the concept stage.

The major disadvantages of the Waterfall Model are as follows −

•	No working software is produced until late during the life cycle.

•	High amounts of risk and uncertainty.

•	Not a good model for complex and object-oriented projects.

•	Poor model for long and ongoing projects.

•	Not suitable for the projects where requirements are at a moderate to high risk of changing. So, risk and uncertainty is high with this process model.

•	It is difficult to measure progress within stages.

•	Cannot accommodate changing requirements.

•	Adjusting scope during the life cycle can end a project.

•	Integration is done as a "big-bang. at the very end, which doesn't allow identifying any technological or business bottleneck or challenges early.

# SDLC - Iterative Model
In the Iterative model, iterative process starts with a simple implementation of a small set of the software requirements and iteratively enhances the evolving versions until the complete system is implemented and ready to be deployed.

An iterative life cycle model does not attempt to start with a full specification of requirements. Instead, development begins by specifying and implementing just part of the software, which is then reviewed to identify further requirements. This process is then repeated, producing a new version of the software at the end of each iteration of the model.

# Iterative Model - Design
Iterative process starts with a simple implementation of a subset of the software requirements and iteratively enhances the evolving versions until the full system is implemented. At each iteration, design modifications are made and new functional capabilities are added. The basic idea behind this method is to develop a system through repeated cycles (iterative) and in smaller portions at a time (incremental).

The following illustration is a representation of the Iterative and Incremental model −
 
Iterative and Incremental development is a combination of both iterative design or iterative method and incremental build model for development. "During software development, more than one iteration of the software development cycle may be in progress at the same time." This process may be described as an "evolutionary acquisition" or "incremental build" approach."

In this incremental model, the whole requirement is divided into various builds. During each iteration, the development module goes through the requirements, design, implementation and testing phases. Each subsequent release of the module adds function to the previous release. The process continues till the complete system is ready as per the requirement.

The key to a successful use of an iterative software development lifecycle is rigorous validation of requirements, and verification & testing of each version of the software against those requirements within each cycle of the model. As the software evolves through successive cycles, tests must be repeated and extended to verify each version of the software.

# Iterative Model - Application
Like other SDLC models, Iterative and incremental development has some specific applications in the software industry. This model is most often used in the following scenarios −

•	Requirements of the complete system are clearly defined and understood.

•	Major requirements must be defined; however, some functionalities or requested enhancements may evolve with time.

•	There is a time to the market constraint.

•	A new technology is being used and is being learnt by the development team while working on the project.

•	Resources with needed skill sets are not available and are planned to be used on contract basis for specific iterations.

•	There are some high-risk features and goals which may change in the future.

# Iterative Model - Pros and Cons
The advantage of this model is that there is a working model of the system at a very early stage of development, which makes it easier to find functional or design flaws. Finding issues at an early stage of development enables to take corrective measures in a limited budget.

The disadvantage with this SDLC model is that it is applicable only to large and bulky software development projects. This is because it is hard to break a small software system into further small serviceable increments/modules.

The advantages of the Iterative and Incremental SDLC Model are as follows −

•	Some working functionality can be developed quickly and early in the life cycle.

•	Results are obtained early and periodically.

•	Parallel development can be planned.

•	Progress can be measured.

•	Less costly to change the scope/requirements.

•	Testing and debugging during smaller iteration is easy.

•	Risks are identified and resolved during iteration; and each iteration is an easily managed milestone.

•	Easier to manage risk - High risk part is done first.

•	With every increment, operational product is delivered.

•	Issues, challenges and risks identified from each increment can be utilized/applied to the next increment.

•	Risk analysis is better.

•	It supports changing requirements.

•	Initial Operating time is less.

•	Better suited for large and mission-critical projects.

•	During the life cycle, software is produced early which facilitates customer evaluation and feedback.

The disadvantages of the Iterative and Incremental SDLC Model are as follows −

•	More resources may be required.

•	Although cost of change is lesser, but it is not very suitable for changing requirements.

•	More management attention is required.

•	System architecture or design issues may arise because not all requirements are gathered in the beginning of the entire life cycle.

•	Defining increments may require definition of the complete system.

•	Not suitable for smaller projects.

•	Management complexity is more.

•	End of project may not be known which is a risk.

•	Highly skilled resources are required for risk analysis.

•	Projects progress is highly dependent upon the risk analysis phase.

# SDLC - Spiral Model
The spiral model combines the idea of iterative development with the systematic, controlled aspects of the waterfall model. This Spiral model is a combination of iterative development process model and sequential linear development model i.e. the waterfall model with a very high emphasis on risk analysis. It allows incremental releases of the product or incremental refinement through each iteration around the spiral.

# Spiral Model - Design
The spiral model has four phases. A software project repeatedly passes through these phases in iterations called Spirals.

# Identification 
This phase starts with gathering the business requirements in the baseline spiral. In the subsequent spirals as the product matures, identification of system requirements, subsystem requirements and unit requirements are all done in this phase.
This phase also includes understanding the system requirements by continuous communication between the customer and the system analyst. At the end of the spiral, the product is deployed in the identified market.

# Design
The Design phase starts with the conceptual design in the baseline spiral and involves architectural design, logical design of modules, physical product design and the final design in the subsequent spirals.

# Construct or Build
The Construct phase refers to production of the actual software product at every spiral. In the baseline spiral, when the product is just thought of and the design is being developed a POC (Proof of Concept) is developed in this phase to get customer feedback.
Then in the subsequent spirals with higher clarity on requirements and design details a working model of the software called build is produced with a version number. These builds are sent to the customer for feedback.

# Evaluation and Risk Analysis
Risk Analysis includes identifying, estimating and monitoring the technical feasibility and management risks, such as schedule slippage and cost overrun. After testing the build, at the end of first iteration, the customer evaluates the software and provides feedback.
The following illustration is a representation of the Spiral Model, listing the activities in each phase.
 
Based on the customer evaluation, the software development process enters the next iteration and subsequently follows the linear approach to implement the feedback suggested by the customer. The process of iterations along the spiral continues throughout the life of the software.

# Spiral Model Application
The Spiral Model is widely used in the software industry as it is in sync with the natural development process of any product, i.e. learning with maturity which involves minimum risk for the customer as well as the development firms.

The following pointers explain the typical uses of a Spiral Model −

•	When there is a budget constraint and risk evaluation is important.

•	For medium to high-risk projects.

•	Long-term project commitment because of potential changes to economic priorities as the requirements change with time.

•	Customer is not sure of their requirements which is usually the case.

•	Requirements are complex and need evaluation to get clarity.

•	New product line which should be released in phases to get enough customer feedback.

•	Significant changes are expected in the product during the development cycle.

# Spiral Model - Pros and Cons
The advantage of spiral lifecycle model is that it allows elements of the product to be added in, when they become available or known. This assures that there is no conflict with previous requirements and design.

This method is consistent with approaches that have multiple software builds and releases which allows making an orderly transition to a maintenance activity. Another positive aspect of this method is that the spiral model forces an early user involvement in the system development effort.

On the other side, it takes a very strict management to complete such products and there is a risk of running the spiral in an indefinite loop. So, the discipline of change and the extent of taking change requests is very important to develop and deploy the product successfully.

The advantages of the Spiral SDLC Model are as follows −

•	Changing requirements can be accommodated.

•	Allows extensive use of prototypes.

•	Requirements can be captured more accurately.

•	Users see the system early.

•	Development can be divided into smaller parts and the risky parts can be developed earlier which helps in better risk management.

The disadvantages of the Spiral SDLC Model are as follows −

•	Management is more complex.

•	End of the project may not be known early.

•	Not suitable for small or low risk projects and could be expensive for small projects.

•	Process is complex

•	Spiral may go on indefinitely.

•	Large number of intermediate stages requires excessive documentation.

# SDLC - V-Model
The V-model is an SDLC model where execution of processes happens in a sequential manner in a V-shape. It is also known as Verification and Validation model.
The V-Model is an extension of the waterfall model and is based on the association of a testing phase for each corresponding development stage. This means that for every single phase in the development cycle, there is a directly associated testing phase. This is a highly-disciplined model and the next phase starts only after completion of the previous phase.

# V-Model - Design
Under the V-Model, the corresponding testing phase of the development phase is planned in parallel. So, there are Verification phases on one side of the ‘V’ and Validation phases on the other side. The Coding Phase joins the two sides of the V-Model.
The following illustration depicts the different phases in a V-Model of the SDLC.
 
# V-Model - Verification Phases
There are several Verification phases in the V-Model, each of these are explained in detail below.

# Business Requirement Analysis
This is the first phase in the development cycle where the product requirements are understood from the customer’s perspective. This phase involves detailed communication with the customer to understand his expectations and exact requirement. This is a very important activity and needs to be managed well, as most of the customers are not sure about what exactly they need. The acceptance test design planning is done at this stage as business requirements can be used as an input for acceptance testing.

# System Design
Once you have the clear and detailed product requirements, it is time to design the complete system. The system design will have the understanding and detailing the complete hardware and communication setup for the product under development. The system test plan is developed based on the system design. Doing this at an earlier stage leaves more time for the actual test execution later.
# Architectural Design
Architectural specifications are understood and designed in this phase. Usually more than one technical approach is proposed and based on the technical and financial feasibility the final decision is taken. The system design is broken down further into modules taking up different functionality. This is also referred to as High Level Design (HLD).

The data transfer and communication between the internal modules and with the outside world (other systems) is clearly understood and defined in this stage. With this information, integration tests can be designed and documented during this stage.
# Module Design
In this phase, the detailed internal design for all the system modules is specified, referred to as Low Level Design (LLD). It is important that the design is compatible with the other modules in the system architecture and the other external systems. The unit tests are an essential part of any development process and helps eliminate the maximum faults and errors at a very early stage. These unit tests can be designed at this stage based on the internal module designs.
# Coding Phase
The actual coding of the system modules designed in the design phase is taken up in the Coding phase. The best suitable programming language is decided based on the system and architectural requirements.

The coding is performed based on the coding guidelines and standards. The code goes through numerous code reviews and is optimized for best performance before the final build is checked into the repository.

# Validation Phases
The different Validation Phases in a V-Model are explained in detail below.
# Unit Testing
Unit tests designed in the module design phase are executed on the code during this validation phase. Unit testing is the testing at code level and helps eliminate bugs at an early stage, though all defects cannot be uncovered by unit testing.
# Integration Testing
Integration testing is associated with the architectural design phase. Integration tests are performed to test the coexistence and communication of the internal modules within the system.
# System Testing
System testing is directly associated with the system design phase. System tests check the entire system functionality and the communication of the system under development with external systems. Most of the software and hardware compatibility issues can be uncovered during this system test execution.
# Acceptance Testing
Acceptance testing is associated with the business requirement analysis phase and involves testing the product in user environment. Acceptance tests uncover the compatibility issues with the other systems available in the user environment. It also discovers the non-functional issues such as load and performance defects in the actual user environment.

# V- Model ─ Application
V- Model application is almost the same as the waterfall model, as both the models are of sequential type. Requirements have to be very clear before the project starts, because it is usually expensive to go back and make changes. This model is used in the medical development field, as it is strictly a disciplined domain.

The following pointers are some of the most suitable scenarios to use the V-Model application.

•	Requirements are well defined, clearly documented and fixed.

•	Product definition is stable.

•	Technology is not dynamic and is well understood by the project team.

•	There are no ambiguous or undefined requirements.

•	The project is short.

# V-Model - Pros and Cons
The advantage of the V-Model method is that it is very easy to understand and apply. The simplicity of this model also makes it easier to manage. The disadvantage is that the model is not flexible to changes and just in case there is a requirement change, which is very common in today’s dynamic world, it becomes very expensive to make the change.

The advantages of the V-Model method are as follows −

•	This is a highly-disciplined model and Phases are completed one at a time.

•	Works well for smaller projects where requirements are very well understood.

•	Simple and easy to understand and use.

•	Easy to manage due to the rigidity of the model. Each phase has specific deliverables and a review process.

The disadvantages of the V-Model method are as follows −

•	High risk and uncertainty.

•	Not a good model for complex and object-oriented projects.

•	Poor model for long and ongoing projects.

•	Not suitable for the projects where requirements are at a moderate to high risk of changing.

•	Once an application is in the testing stage, it is difficult to go back and change a functionality.

•	No working software is produced until late during the life cycle.

# SDLC - Big Bang Model
The Big Bang model is an SDLC model where we do not follow any specific process. The development just starts with the required money and efforts as the input, and the output is the software developed which may or may not be as per customer requirement. This Big Bang Model does not follow a process/procedure and there is a very little planning required. Even the customer is not sure about what exactly he wants and the requirements are implemented on the fly without much analysis.
Usually this model is followed for small projects where the development teams are very small.
# Big Bang Model ─ Design and Application
The Big Bang Model comprises of focusing all the possible resources in the software development and coding, with very little or no planning. The requirements are understood and implemented as they come. Any changes required may or may not need to revamp the complete software.
This model is ideal for small projects with one or two developers working together and is also useful for academic or practice projects. It is an ideal model for the product where requirements are not well understood and the final release date is not given.
# Big Bang Model - Pros and Cons
The advantage of this Big Bang Model is that it is very simple and requires very little or no planning. Easy to manage and no formal procedure are required.
However, the Big Bang Model is a very high risk model and changes in the requirements or misunderstood requirements may even lead to complete reversal or scraping of the project. It is ideal for repetitive or small projects with minimum risks.

The advantages of the Big Bang Model are as follows −

•	This is a very simple model

•	Little or no planning required

•	Easy to manage

•	Very few resources required

•	Gives flexibility to developers

•	It is a good learning aid for new comers or students.

The disadvantages of the Big Bang Model are as follows −

•	Very High risk and uncertainty.

•	Not a good model for complex and object-oriented projects.

•	Poor model for long and ongoing projects.

•	Can turn out to be very expensive if requirements are misunderstood.

# SDLC - Agile Model
Agile SDLC model is a combination of iterative and incremental process models with focus on process adaptability and customer satisfaction by rapid delivery of working software product. Agile Methods break the product into small incremental builds. These builds are provided in iterations. Each iteration typically lasts from about one to three weeks. Every iteration involves cross functional teams working simultaneously on various areas like −

•	Planning

•	Requirements Analysis

•	Design

•	Coding

•	Unit Testing and

•	Acceptance Testing.

At the end of the iteration, a working product is displayed to the customer and important stakeholders.

# What is Agile?
Agile model believes that every project needs to be handled differently and the existing methods need to be tailored to best suit the project requirements. In Agile, the tasks are divided to time boxes (small time frames) to deliver specific features for a release.
Iterative approach is taken and working software build is delivered after each iteration. Each build is incremental in terms of features; the final build holds all the features required by the customer.

Here is a graphical illustration of the Agile Model −
 
The Agile thought process had started early in the software development and started becoming popular with time due to its flexibility and adaptability.
The most popular Agile methods include Rational Unified Process (1994), Scrum (1995), Crystal Clear, Extreme Programming (1996), Adaptive Software Development, Feature Driven Development, and Dynamic Systems Development Method (DSDM) (1995). These are now collectively referred to as Agile Methodologies, after the Agile Manifesto was published in 2001.

Following are the Agile Manifesto principles −

•	Individuals and interactions − In Agile development, self-organization and motivation are important, as are interactions like co-location and pair programming.

•	Working software − Demo working software is considered the best means of communication with the customers to understand their requirements, instead of just depending on documentation.

•	Customer collaboration − As the requirements cannot be gathered completely in the beginning of the project due to various factors, continuous customer interaction is very important to get proper product requirements.

•	Responding to change − Agile Development is focused on quick responses to change and continuous development.

# Agile Vs Traditional SDLC Models
Agile is based on the adaptive software development methods, whereas the traditional SDLC models like the waterfall model is based on a predictive approach. Predictive teams in the traditional SDLC models usually work with detailed planning and have a complete forecast of the exact tasks and features to be delivered in the next few months or during the product life cycle.

Predictive methods entirely depend on the requirement analysis and planning done in the beginning of cycle. Any changes to be incorporated go through a strict change control management and prioritization.

Agile uses an adaptive approach where there is no detailed planning and there is clarity on future tasks only in respect of what features need to be developed. There is feature driven development and the team adapts to the changing product requirements dynamically. The product is tested very frequently, through the release iterations, minimizing the risk of any major failures in future.

Customer Interaction is the backbone of this Agile methodology, and open communication with minimum documentation are the typical features of Agile development environment. The agile teams work in close collaboration with each other and are most often located in the same geographical location.

# Agile Model - Pros and Cons
Agile methods are being widely accepted in the software world recently. However, this method may not always be suitable for all products. Here are some pros and cons of the Agile model.

The advantages of the Agile Model are as follows −

•	Is a very realistic approach to software development.

•	Promotes teamwork and cross training.

•	Functionality can be developed rapidly and demonstrated.

•	Resource requirements are minimum.

•	Suitable for fixed or changing requirements

•	Delivers early partial working solutions.

•	Good model for environments that change steadily.

•	Minimal rules, documentation easily employed.

•	Enables concurrent development and delivery within an overall planned context.

•	Little or no planning required.

•	Easy to manage.

•	Gives flexibility to developers.

The disadvantages of the Agile Model are as follows −

•	Not suitable for handling complex dependencies.

•	More risk of sustainability, maintainability and extensibility.

•	An overall plan, an agile leader and agile PM practice is a must without which it will not work.

•	Strict delivery management dictates the scope, functionality to be delivered, and adjustments to meet the deadlines.

•	Depends heavily on customer interaction, so if customer is not clear, team can be driven in the wrong direction.

•	There is a very high individual dependency, since there is minimum documentation generated.

•	Transfer of technology to new team members may be quite challenging due to lack of documentation.

# SDLC - RAD Model
The RAD (Rapid Application Development) model is based on prototyping and iterative development with no specific planning involved. The process of writing the software itself involves the planning required for developing the product.
Rapid Application Development focuses on gathering customer requirements through workshops or focus groups, early testing of the prototypes by the customer using iterative concept, reuse of the existing prototypes (components), continuous integration and rapid delivery.

What is RAD?
Rapid application development is a software development methodology that uses minimal planning in favor of rapid prototyping. A prototype is a working model that is functionally equivalent to a component of the product.

In the RAD model, the functional modules are developed in parallel as prototypes and are integrated to make the complete product for faster product delivery. Since there is no detailed preplanning, it makes it easier to incorporate the changes within the development process.
RAD projects follow iterative and incremental model and have small teams comprising of developers, domain experts, customer representatives and other IT resources working progressively on their component or prototype.
The most important aspect for this model to be successful is to make sure that the prototypes developed are reusable.
# RAD Model Design
RAD model distributes the analysis, design, build and test phases into a series of short, iterative development cycles.



Following are the various phases of the RAD Model –

Business Modelling

The business model for the product under development is designed in terms of flow of information and the distribution of information between various business channels. A complete business analysis is performed to find the vital information for business, how it can be obtained, how and when is the information processed and what are the factors driving successful flow of information.

Data Modelling

The information gathered in the Business Modelling phase is reviewed and analyzed to form sets of data objects vital for the business. The attributes of all data sets is identified and defined. The relation between these data objects are established and defined in detail in relevance to the business model.

Process Modelling

The data object sets defined in the Data Modelling phase are converted to establish the business information flow needed to achieve specific business objectives as per the business model. The process model for any changes or enhancements to the data object sets is defined in this phase. Process descriptions for adding, deleting, retrieving or modifying a data object are given.

Application Generation

The actual system is built and coding is done by using automation tools to convert process and data models into actual prototypes.

Testing and Turnover

The overall testing time is reduced in the RAD model as the prototypes are independently tested during every iteration. However, the data flow and the interfaces between all the components need to be thoroughly tested with complete test coverage. Since most of the programming components have already been tested, it reduces the risk of any major issues.


The following illustration describes the RAD Model in detail.
 
# RAD Model Vs Traditional SDLC
The traditional SDLC follows a rigid process models with high emphasis on requirement analysis and gathering before the coding starts. It puts pressure on the customer to sign off the requirements before the project starts and the customer doesn’t get the feel of the product as there is no working build available for a long time.
The customer may need some changes after he gets to see the software. However, the change process is quite rigid and it may not be feasible to incorporate major changes in the product in the traditional SDLC.
The RAD model focuses on iterative and incremental delivery of working models to the customer. This results in rapid delivery to the customer and customer involvement during the complete development cycle of product reducing the risk of non-conformance with the actual user requirements.

# RAD Model - Application
RAD model can be applied successfully to the projects in which clear modularization is possible. If the project cannot be broken into modules, RAD may fail.

The following pointers describe the typical scenarios where RAD can be used −

•	RAD should be used only when a system can be modularized to be delivered in an incremental manner.

•	It should be used if there is a high availability of designers for Modelling.

•	It should be used only if the budget permits use of automated code generating tools.

•	RAD SDLC model should be chosen only if domain experts are available with relevant business knowledge.

•	Should be used where the requirements change during the project and working prototypes are to be presented to customer in small iterations of 2-3 months.

# RAD Model - Pros and Cons
RAD model enables rapid delivery as it reduces the overall development time due to the reusability of the components and parallel development. RAD works well only if high skilled engineers are available and the customer is also committed to achieve the targeted prototype in the given time frame. If there is commitment lacking on either side the model may fail.

The advantages of the RAD Model are as follows −

•	Changing requirements can be accommodated.

•	Progress can be measured.

•	Iteration time can be short with use of powerful RAD tools.

•	Productivity with fewer people in a short time.

•	Reduced development time.

•	Increases reusability of components.

•	Quick initial reviews occur.

•	Encourages customer feedback.

•	Integration from very beginning solves a lot of integration issues.

The disadvantages of the RAD Model are as follows −

•	Dependency on technically strong team members for identifying business requirements.

•	Only system that can be modularized can be built using RAD.

•	Requires highly skilled developers/designers.

•	High dependency on Modelling skills.

•	Inapplicable to cheaper projects as cost of Modelling and automated code generation is very high.

•	Management complexity is more.

•	Suitable for systems that are component based and scalable.

•	Requires user involvement throughout the life cycle.

•	Suitable for project requiring shorter development times.

# SDLC - Software Prototype Model
The Software Prototyping refers to building software application prototypes which displays the functionality of the product under development, but may not actually hold the exact logic of the original software.

Software prototyping is becoming very popular as a software development model, as it enables to understand customer requirements at an early stage of development. It helps get valuable feedback from the customer and helps software designers and developers understand about what exactly is expected from the product under development.

# What is Software Prototyping?
Prototype is a working model of software with some limited functionality. The prototype does not always hold the exact logic used in the actual software application and is an extra effort to be considered under effort estimation.
Prototyping is used to allow the users evaluate developer proposals and try them out before implementation. It also helps understand the requirements which are user specific and may not have been considered by the developer during product design.

Following is a stepwise approach explained to design a software prototype.

# Basic Requirement Identification
This step involves understanding the very basics product requirements especially in terms of user interface. The more intricate details of the internal design and external aspects like performance and security can be ignored at this stage.
# Developing the initial Prototype
The initial Prototype is developed in this stage, where the very basic requirements are showcased and user interfaces are provided. These features may not exactly work in the same manner internally in the actual software developed. While, the workarounds are used to give the same look and feel to the customer in the prototype developed.
# Review of the Prototype
The prototype developed is then presented to the customer and the other important stakeholders in the project. The feedback is collected in an organized manner and used for further enhancements in the product under development.
# Revise and Enhance the Prototype
The feedback and the review comments are discussed during this stage and some negotiations happen with the customer based on factors like – time and budget constraints and technical feasibility of the actual implementation. The changes accepted are again incorporated in the new Prototype developed and the cycle repeats until the customer expectations are met.

Prototypes can have horizontal or vertical dimensions. A Horizontal prototype displays the user interface for the product and gives a broader view of the entire system, without concentrating on internal functions. A Vertical prototype on the other side is a detailed elaboration of a specific function or a sub system in the product.

The purpose of both horizontal and vertical prototype is different. Horizontal prototypes are used to get more information on the user interface level and the business requirements. It can even be presented in the sales demos to get business in the market. Vertical prototypes are technical in nature and are used to get details of the exact functioning of the sub systems. For example, database requirements, interaction and data processing loads in a given sub system.

# Software Prototyping - Types
There are different types of software prototypes used in the industry. Following are the major software prototyping types used widely −

Throwaway/Rapid Prototyping

Throwaway prototyping is also called as rapid or close ended prototyping. This type of prototyping uses very little efforts with minimum requirement analysis to build a prototype. Once the actual requirements are understood, the prototype is discarded and the actual system is developed with a much clear understanding of user requirements.

Evolutionary Prototyping

Evolutionary prototyping also called as breadboard prototyping is based on building actual functional prototypes with minimal functionality in the beginning. The prototype developed forms the heart of the future prototypes on top of which the entire system is built. By using evolutionary prototyping, the well-understood requirements are included in the prototype and the requirements are added as and when they are understood.

Incremental Prototyping

Incremental prototyping refers to building multiple functional prototypes of the various sub-systems and then integrating all the available prototypes to form a complete system.

Extreme Prototyping

Extreme prototyping is used in the web development domain. It consists of three sequential phases. First, a basic prototype with all the existing pages is presented in the HTML format. Then the data processing is simulated using a prototype services layer. Finally, the services are implemented and integrated to the final prototype. This process is called Extreme Prototyping used to draw attention to the second phase of the process, where a fully functional UI is developed with very little regard to the actual services.

Software Prototyping - Application

Software Prototyping is most useful in development of systems having high level of user interactions such as online systems. Systems which need users to fill out forms or go through various screens before data is processed can use prototyping very effectively to give the exact look and feel even before the actual software is developed.

Software that involves too much of data processing and most of the functionality is internal with very little user interface does not usually benefit from prototyping. Prototype development could be an extra overhead in such projects and may need lot of extra efforts.

Software Prototyping - Pros and Cons

Software prototyping is used in typical cases and the decision should be taken very carefully so that the efforts spent in building the prototype add considerable value to the final software developed. The model has its own pros and cons discussed as follows.

The advantages of the Prototyping Model are as follows −

•	Increased user involvement in the product even before its implementation.

•	Since a working model of the system is displayed, the users get a better understanding of the system being develope

•	Reduces time and cost as the defects can be detected much earlier.

•	Quicker user feedback is available leading to better solutions.

•	Missing functionality can be identified easily.

•	Confusing or difficult functions can be identified.

The Disadvantages of the Prototyping Model are as follows −

•	Risk of insufficient requirement analysis owing to too much dependency on the prototype.

•	Users may get confused in the prototypes and actual systems.
•	Practically, this methodology may increase the complexity of the system as scope of the system may expand beyond original plans.

•	Developers may try to reuse the existing prototypes to build the actual system, even when it is not technically feasible.

•	The effort invested in building prototypes may be too much if it is not monitored properly.


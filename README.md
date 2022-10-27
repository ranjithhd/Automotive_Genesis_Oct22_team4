# Automotive_Genesis_Oct22_team4

## Day1_activity_2

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


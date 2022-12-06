# Remote Sensing

<!--toc:start-->
- [Remote Sensing](#remote-sensing)
  - [Elements of remote sensing](#elements-of-remote-sensing)
  - [Electromagnetic Radiation](#electromagnetic-radiation)
  - [Interactions in the Atmosphere](#interactions-in-the-atmosphere)
    - [Scattering: Particles and large molecules in the atmosphere interact with EMR redirecting it from its original path](#scattering-particles-and-large-molecules-in-the-atmosphere-interact-with-emr-redirecting-it-from-its-original-path)
      - [Rayleigh Scattering:](#rayleigh-scattering)
      - [Mie Scattering](#mie-scattering)
      - [Nonselective scattering](#nonselective-scattering)
    - [Absorption: Involves molecules in the atmosphere absorbing energy](#absorption-involves-molecules-in-the-atmosphere-absorbing-energy)
      - [Ozone:](#ozone)
      - [Carbon dioxide:](#carbon-dioxide)
    - [3 Broad Categories of Remote Sensing Platforms](#3-broad-categories-of-remote-sensing-platforms)
<!--toc:end-->

Remote sensing is a general name referring to all methods of collecting data about an object (in this case the earth)
without making physical contact with that object (at some distance from the object of study), by some kind of recording device.  
According to the above definition, a pair of binoculars and an ordinary camera are simple remote sensing systems.  
During World War II, two new remote sensing methods were developed, sonar and radar.  

> According to the [Canada Center for Remote Sensing](https://www.nrcan.gc.ca/maps-tools-and-publications/satellite-imagery-and-air-photos/tutorial-fundamentals-remote-sensing/introduction/9363):  
Remote sensing, is the science (and to some extent art) of obtaining information
about the Earth's surface, without actually being in contact with it. This is done by sensing and recording reflected and emitted
energy, and processing, analysing and applying that information.

The process of remote sensing mostly involves an interaction of incident radiation and the targets of interest.
Thus remote sensing systems are divided into two based on their separate technical solution. **Passive (Optical) remote sensing systems** measure
existing radiation, such as reflected solar radiation from the earth's surface. **Active remote (Satellite) sensing systems** emit radiation 
(micro and radio waves) on the object and measure the amount of reflected radiation.  

Satellite remote sensing refers to all methods of getting information about an object from a distance by measuring the radiation emitted,
reflected or absorbed by the object.

An ordinary camera is an example of a passive remote sensing system, using existing light as an input. If a flash is added to the camera,
it becomes an active remote-sensing system, since it then provides the necessary radiation, without considering existing radiation sources.  

Examples of active remote sensing systems are Radar, Sonar, Echo-location and more recently Lidar which uses laser technology to emit and then
collect reflection from the surface of the target object(Earth). Examples of passive remote-sensing systems include Photography, Scanning
Mirrors (MSS), and Push Broom Scanner.

> Active remote sensing uses micro and radio waves because of their larger wavelengths, which allows them to obstacles such as the clouds and 
small vegetation, which is are often limitation of Optical remote sensing.

|Active Remote Sensing|Images|
|:--------------------:|:----:|
|Radar sensing devices|![radar sensing devices](https://www.ruangteknisi.com/wp-content/uploads/2022/03/Gambar-bentuk-sensor-radar.jpg)|
|Lidar image|![imgae of a landscape taken with lidar](https://oceanservice.noaa.gov/facts/remote-sensing.jpg)|
|A plane collecting lidar image|![a plane collecting lidar imgae](https://www.researchgate.net/publication/314234131/figure/fig1/AS:779409451663360@1562837102076/A-landscape-scale-airborne-LiDAR-data-acquisition-system-courtesy-of-ASPRS.gif)|

## Elements of remote sensing
* Energy source or Illumination: this source illuminates the target of interest.
* Radiation and the atmosphere: the light comes in contact with the atmosphere as it travels from the source to the target.
* Interaction with the object: the interaction between the target and the light, is dependent on both their properties.
* Recording of energy/data by the sensor: the interaction gives us data that we collect remotely through some sensors.
* Transmission, Reception and processing: that data is then transmitted to a receiving and processing station, where it is processed.
* Interpretation and analysis: the processed data which is usually now in the form of an image, is then analyzed to extract information.
* Application: the information can now be applied to solving a particular problem.

## Electromagnetic Radiation
The first requirement for remote sensing is to have an energy source illuminate the target (unless the sensed radiation is being emitted
by the target). This energy is in the form of electromagnetic radiation.  
Two characteristics of electromagnetic waves are particularly important to understanding remote sensing: **wavelength and frequency**.

    c = v.λ
    where:  
    c is the speed of light,
    v is the frequency of the wave,
    and λ is the wavelength of the wave
as **c** is fairly constant, the wavelength and frequency are inversely related.  

In remote sensing applications, electromagnetic energy is usually classified according to its location in the electromagnetic
spectrum that is by its wavelength.
![electromagnetic magnetic spectrum](https://www.researchgate.net/publication/258241350/figure/fig2/AS:614122790072322@1523429691663/Diagram-of-the-lights-electromagnetic-spectrum-showing-the-different-wavelengths-of.png)At the lower end (shorter wavelength and higher frequency) we have **Gamma rays**, while at the higher end (longer wavelength and lower 
frequency) we have **Radio waves**.
> In remote sensing, we are more concerned with wavelength than frequency. The most common unit for measuring wavelength is the 
micrometer (μm) which is 10<sup>-6</sup>m, but the ISO (International system unit) is nanometer which is 10<sup>-9</sup>

## Interactions in the Atmosphere
Particles in the atmosphere can affect the incoming light through **Scattering** and **Absorption**.
### Scattering: Particles and large molecules in the atmosphere interact with EMR redirecting it from its original path
- This is affected by factors such as the wavelength of the radiation, the abundance of particles, and the
  distance the radiation travels through the atmosphere.
- There are three(3) types of scattering that take place.
    * Rayleigh Scattering
    * Mie Scattering
    * Nonselective scattering

#### Rayleigh Scattering:
Occurs when the particles in the atmosphere are very small relative to the wavelength of the radiation and thus cause shorter
wavelengths of energy to scatter more than the longer wavelengths, these particles may include small dust specs, nitrogen,
or oxygen molecules.  
This form of scattering is the most dominant form of scattering in the atmosphere and is the reason, the sky appears blue
because blue light has a lower wavelength, and thus it is scattered in the atmosphere more than the rest.

#### Mie Scattering
Occurs when particles are just about the same size as the radiation wavelength. This type of scattering tends to affect
larger wavelengths than those affected by Rayleigh Scattering.

#### Nonselective scattering
Occurs when particles are far larger than the wavelengths of incoming radiation leading to wavelengths being scattered
equally. This is usually caused by water droplets and large dust particles. This kind of scattering causes fog and clouds to
appear white to our eyes because most of the wavelengths of light are scattered.

### Absorption: Involves molecules in the atmosphere absorbing energy
- This involves molecules in the atmosphere absorbing energy at various wavelengths.
- Ozone, carbon dioxide and water vapor are the three main perpetrators of this act.

#### Ozone:
Absorbs the harmful ultraviolet radiation from the sun, which could lead to skin burns.

#### Carbon dioxide:
Popularly known as a greenhouse gas because it tends to absorb EMRs in the infrared region which is associated with
heating and thus serves to trap heat inside the atmosphere.


The presence of these gasses in the atmosphere influence where in the spectrum we can look. Those areas in the spectrum that
are not severely influenced by atmospheric absorption and are useful to remote sensors are called **atmospheric windows**.

### 3 Broad Categories of Remote Sensing Platforms
* Ground-based remote sensing.
* Airborne remote sensing.
* Satellite-based remote sensing
> I'll say that any of the kinds or remote sensing (Active remote sensing and Passive remote sensing), can fall into any of these categories.

# Utilidata, How they are utilizing AI

**Utilidata** is a privately held company that was found by Jeremy Wilson on January 31, 2012.  They are [headquartered](https://www.crunchbase.com/organization/utilidata) in Providence, Rhoad Island. Their innovation lab is in Ann Arbor, Michigan.  There are approximately 71 employees.  


They started as a software company to help substation equipment run more efficiently through Volt/VAR optimization.  Volt-Var (VVC) is the control of electricity to maintain acceptable voltages at all points in the distribution.  Bob Uluski at EPRI has presented on Volt-Var and additonal details can be found here. [Volt/Var](https://nwess-archive.ece.uw.edu/2012/talks/uluski.pdf)

The company has had several rounds of funding.  Their latest round was a Series B worth $26.7M.  They have received [$51.5M](https://www.cbinsights.com/company/utilidata/financials) over 8 rounds of funding in total.

The folowing press release talks about this lates round of funding in more detail.  [Press Release](https://www.prnewswire.com/news-releases/utilidata-raises-26-75-million-to-accelerate-the-clean-energy-transition-301477509.html)


## Business Activities

Utilidata's primary focus is to help buildings be better equipped to handle the dynamically changing grid conditions by leveraging real time data and analytics to  increasing energy efficiency for home owners and building operators and help utilties minimize losses during transmission and distribution.

They sell their products, which are primarily software and embeded devices to meter manufacturers.  The meters are being used on commercial and residential buildings by various utilities.

One of Utilidata's primary product called Karman.  It’s an edge device that communicates with the cloud that utilizes Nvidia’s Jetson platform.  It looks like a smart meter that is installed on building.  It monitors the grid and the signal coming into a building, and then using their AI algorithms to helps the building respond in real time to how the grid is performing.

They recently closed a large deal with Aclara, a part of Hubblell, the third largest meter manufacture in the US.

> According to [Hubbell’s](https://hubbell.gcs-web.com/news-releases/news-release-details/aclara-partners-utilidata-bring-distributed-ai-grid-edge) press release, “As the grid becomes increasingly more complex and dynamic, utilities need more technology options to operate a clean and reliable grid. By combining Utilidata’s extensive knowledge of distributed AI with Aclara’s decades of experience providing industry-leading hardware, we’re now able to bring new, innovative, interoperable solutions to our customers, starting with smart meters.”

---

The technology uses their algorithms to anticipate large load and spread them out so that there are no overloads.  Think of an example in a neighborhood where everyone has an electric car.  They all come home and plug in their cars and then do the laundry, wash the dishes, and turn on all their devices in the house.  If everyone on the neighborhood did this all at once, it would overload the local grid or transformer, and then no one would have power.  Their smart meters monitor and then anticipate using AI to better manage the loads, as well as the sources of electricity, be it from solar, batteries, wind, etc, that maybe supplied to the neighborhood.

One of the benefits of their technology is helping the grid better manage the loads.  It’s estimated that the grid is oversized by [50%](https://www.forbes.com/sites/erikkobayashisolomon/2024/04/23/utilidatas-ai-sharpens-the-grids-edge/?sh=42f8ed9178fd) in order to handle peak demands.  If these loads can be spread out, the utilities can prevent the cost to add additional capacity that may not be used.

---

Their technology is built on Nvidia’s Jetson platform.  Based on the profile for a [software engineering](https://utilidata.applytojob.com/apply/mGorRTzUqC/Senior-Software-Engineer-EdgeIoT) position at the company, some of the tools and software they use Nvidia ML software stack, Docker, AWS, MQTT, OPC-UA, modbus, SQLite.

## Landscape

Utilidata's primary focus is on embedded software for smart utility meters.  Electrification of the everything from cars, heat pumps, growing need for AI, etc, has driven the demand for electricity.  Utilities are struggling to keep up and are looking for ways to better manage the electricity they do produce without having to add too much excess capacity.  They also have to deal with the variability in renewable energy sources such as solar and wind, as well as manage new and existing power generation equipment.

Two of their primary competitors are [Itron](https://na.itron.com/) and [Landis+Gyr](https://www.landisgyr.com/).

## Recommendations

I would suggest Utilidat continue to build out their products so that they integrate with more equipment in the home or business, such as air conditioner, heat pumps, hot water heaters, washers and dryers, car chargers, on site solar generation.  In additon I think they should provide realtime feedback to the owners and operators of the impact of their tools through easy to use apps and websites.  The impact they should show could be CO2 offset through load shifting, energy saved, how frequently equipment is load shifted and by how much.

This additional offering could help broaden interest in their services.  Right now a lot of demand response programs are voluntary, people have to sign up for them.  This additional service could help make it more attractive to a broader audience and gain greater adoption.

They would need to leverage additional data from distributed devices.  They would need to incorporate additional api’s as well as new data protocols to get the data.  Once they have the new data, they could leverage self learning ML algorithm to learn how the new devices behave, and how to react to them to help the home owner save energy as well as help the utilities be able to provide consistent and reliable power.

The problem they are trying to solve involves a lot of data.  A lot of it is real time.  Being able to process this data, in conjunction with grid level data will be important in real time.  The data is complex and changes frequently, and will require advanced AI/ML algorithms instead of traditional if then else algorithms to respond to the ongoing changes.


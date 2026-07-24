Vactrain Set Readme
-----------------------------------

Contents:

1 About
2 Usage and Parameters
3 Building from source
  3.1 Obtaining the source
4 Credits
5 License



-------
1 About
-------

A set which adds a Vacuum Tube railtype and accompanying trains to OpenTTD, enabling more interesting future gameplay.

Compatible with most popular trainsets as well as the default trainset.



The Vactrain Set is not compatible with any previous versions, outdated addons, or forks.
These will be automatically disabled if detected:

* Vactrain Set 1.0.1 or older
* Vactrain Set Fork
* Vacuum Vehicule [sic] Wagon and Train
* Brianum Vacuum Monorail


Known Bugs

Dual-headed vehicles show incorrect capacity in the purchase window when the capacity parameter is set to something other than the default.


----------------------
2 Usage and Parameters
----------------------

---Vehicles---


The Vactrain Set has 16 train models, split into 4 generations. Each generation features a universal locomotive, a cargo locomotive, a low capacity MU and a high capacity MU.

While the in-tube speed of each generation remains consistent, the atmospheric speed will vary based on model in order to encourage intersting gameplay choices.

The atmospheric speed is the speed the train is able to travel outside of a vacuum tube (i.e. on regular maglev tracks). Some vactrains have a fast enough atmospheric speed to enable them to keep up with contemporary maglev trains. However, others suffer a severe speed penalty when leaving the vacuum tube, so choose carefully depending on your route.



Multiple Units (MUs)
Multiple units are separated into Passenger and Express Freight variants. When Passenger or Express Freight wagons are attached, the wagons boost the power of the train. The wagons also adapt themselves to match the appearance and capacity of the train, and running costs are adjusted accordingly.

Cargo Wagons do not boost the power of MU trains, and will result in the trains being underpowered.


Cargo Engines
These powerful engines are designed to haul cargo, but can also haul passenger wagons if needed. Wagons will not contribute power, so combine more cargo engines to increase acceleration.


Universal engines
These are general purpose engines for either passengers or cargo. Wagons will adapt to appearance and capacity, but will not contribute power.

---Parameters---

Cost Parameters allow to adjust the difficulty to balance it with other GRFs or if you find it too easy to make money.
They allow adjustment of:

* Train Running cost
* Train Purchase costs
* Track Construction
* Track Maintenance

The introduction date parameter allows to adjust the timeline of vehicle releases.
Engines will be released for approximately 100 years after the given year.


Loading Speed
Adjust the loading speeds of vactrain vehicles.


Vehicle capacity
Adjust the capacity of vactrain vehicles.

Conservative = 0.8x capacity
Normal = 1x capacity
Generous = 1.2x capacity



Vehicle Speed
Adjust the maximum speed of the fastest generation of vactrains. The maximum speed of the previous generations of vactrain will be adjusted proportionally. This parameter does not affect the atmospheric speeds, which remain fixed.

The minimum is 1,000 km/h, which offers a subtle but noticeable speed curve over the fastest maglev trains. The default is 2,400 km/h because this offers a significant speed boost without becoming too difficult to attain and maintain.

It is not recommended to set this to extremely high values, as it is nearly impossible for vactrains to reach speeds much over 10,000km/h.


Allow Vactrains on Maglev Tracks
By default, vactrains are allowed on normal maglev tracks, albeit at a significantly reduced top speed. Disable this to keep vactrains as their own separate railtype apart from maglev.

Allow Maglevs on Vactrain Tracks
By default, maglev trains are allowed on vactrain tracks. Disable this to prevent slow maglev trains from going on your vactrain lines, or for realism/roleplay purposes (maglevs are not airtight so the passengers would suffocate!)

Replace Maglev Track Graphics
By default, the Vactrain set replaces the vanilla maglev tracks to match the vactrain tracks. Disable this if you want to use the maglev tracks from the base set or another NewGRF that provides maglev tracks.



---Game Settings---

Infrastructure Maintenance
This is very expensive for vactrain tracks.


When using JGRPP, it is highly recommended to enable "Realistic Braking" as well as "Limit Train Acceleration". This will cause vactrains to accelerate and brake gradually instead of near-instantly, which is more realistic but makes them less practical for short distance trips.

When realistic braking is enabled, vactrains also need much greater gaps between them to allow for the required braking distance. This means that top speed has a significant impact on the capacity of a vactrain line.



----------------------
3 Building from source
----------------------

Just compile the vactrain.nml

3.1 Obtaining the source
------------------------

The source code can be obtained from the GitHub page.
https://github.com/EmperorJake/vactrain


---------
4 Credits
---------

Original Author: Jakob Karl (Emperor Jake) using elements of code by Terkhen, planetmaker, Transportman, FooBar and possibly others

Includes code from the Vactrain Set Fork by Josh Barrass

Artists:
Tracks from FS_Maglev by Froix
Vacuum tube overlay by Zephyris
Depot from OpenGFX Mars by Zephyris
Trains by Emperor Jake, Voyager One, Erato, DJ Nekkid



---------------
5 License
---------------

The Vactrain Set
(c) 2026 Emperor Jake and others

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License along
with this NewGRF; if not, write to the Free Software Foundation, Inc.,
51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.

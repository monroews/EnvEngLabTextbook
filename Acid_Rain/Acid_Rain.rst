% Generated by GrindEQ Word-to-LaTeX
\documentclass{article} %%% use \documentstyle for old LaTeX compilers

\usepackage[english]{babel} %%% 'french', 'german', 'spanish', 'danish', etc.
\usepackage{amssymb}
\usepackage{amsmath}
\usepackage{txfonts}
\usepackage{mathdots}
\usepackage[classicReIm]{kpfonts}
\usepackage[dvips]{graphicx} %%% use 'pdftex' instead of 'dvips' for PDF output

% You can include more LaTeX packages here


\begin{document}

%\selectlanguage{english} %%% remove comment delimiter ('%') and select language if required


 C:{\textbackslash}WINNT{\textbackslash}Profiles{\textbackslash}mlws{\textbackslash}Application Data{\textbackslash}Microsoft{\textbackslash}Templates{\textbackslash}lab manual.dot









.. math::

    1





 Acid Precipitation and Remediation of Acid Lakes

 CEE 4530: \textit{Laboratory Research in Environmental Engineering}Spring, 2018






================
Acid Precipitation and Remediation of PlaceNameplaceAcid PlaceTypeLakes}


------------------
Introduction}

Acid precipitation has been a serious environmental problem in many areas of the world for the last few decades. Acid precipitation results from the combustion of fossil fuels which produce oxides of sulfur and nitrogen that react in the earth's atmosphere to form sulfuric and nitric acid. One of the most significant impacts of acid rain is the acidification of lakes and streams. In some watersheds the soil doesn't provide ample acid neutralizing capacity to mitigate the effect of incident acid precipitation. These susceptible regions are usually high elevation lakes with small watersheds and shallow non-calcareous soils. The underlying bedrock of acid-sensitive lakes tends to be granite or quartz. These minerals are slow to weather and therefore have little capacity to neutralize acids. The relatively short contact time between the acid precipitation and the watershed soil system exacerbates the problem. Lakes most susceptible to acidification: 1) are located downwind, sometimes hundreds of miles downwind, from major pollution sources--electricity generation, metal refining operations, heavy industry, large population centers, etc.; 2) are surrounded by hard, insoluble bedrock with thin, sandy, infertile soil; 3) have a high runoff to infiltration ratio; 4) have a low watershed to lake surface area. Isopleths of precipitation pH are depicted in Figure \eqref{ZEqnNum895787}.

 \includegraphics*[width=5.77in, height=3.49in, keepaspectratio=false]{image1}

 Figure  \label{ZEqnNum895787}. The pH of precipitation in 2009.

In acid-sensitive lakes the major parameter of concern is pH (pH = -logcitation$\mathrm{\{}$H+$\mathrm{\}}$, where citation$\mathrm{\{}$H+$\mathrm{\}}$ is the hydrogen ion activity, and activity is approximately equal to concentration in moles/L). In a healthy lake, ecosystem pH should be in the range of 6.5 to 8.5. In most natural freshwater systems, the dominant pH buffering (controlling) system is the carbonate system. The carbonate buffering system is composed of four components: dissolved carbon dioxide (${\rm CO}_{{\rm 2\; aq}} $), carbonic acid (${\rm H}_{{\rm 2}} {\rm CO}_{{\rm 3}} $), bicarbonate (${\rm HCO}_{{\rm 3}}^{{\rm -}} $), and carbonate (${\rm CO}_{{\rm 3}}^{{\rm -2}} $). Carbonic acid exists only at very low levels in aqueous systems and for purposes of acid neutralization is indistinguishable from dissolved carbon dioxide. Thus to simplify things we define
\begin{equation} \label{ZEqnNum141302}
\left[{\rm H}_{{\rm 2}} {\rm CO}_{{\rm 3}}^{{\rm *}} \right]=\left[{\rm CO}_{{\rm 2\; aq}} \right]+\left[{\rm H}_{{\rm 2}} {\rm CO}_{{\rm 3}} \right]
\end{equation}
The $\left[{\rm CO}_{{\rm 2\; aq}} \right]$ $\mathrm{>}$$\mathrm{>}$ $\left[{\rm H}_{{\rm 2}} {\rm CO}_{{\rm 3}} \right]$ and thus $\left[{\rm H}_{{\rm 2}} {\rm CO}_{{\rm 3}}^{{\rm *}} \right]\cong \left[{\rm CO}_{{\rm 2\; aq}} \right]$ (all terms enclosed in [] are in units of moles/L).

The sum of the molar concentrations of all the components of the carbonate system is designated as CT as shown in equation \eqref{ZEqnNum866451}.
\begin{equation} \label{ZEqnNum866451}
{\rm C}_{{\rm T}} {\rm \; }={\rm \; }\left[{\rm H}_{{\rm 2}} {\rm CO}_{{\rm 3}}^{{\rm *}} \right]{\rm \; }+\left[{\rm HCO}_{{\rm 3}}^{{\rm -}} \right]+{\rm \; }\left[{\rm CO}_{{\rm 3}}^{{\rm -2}} \right]
\end{equation}

The carbonate system can be considered to be a "volatile" system or a "non-volatile" system depending on whether or not aqueous carbon dioxide is allowed to exchange and equilibrate with atmospheric carbon dioxide. Mixing conditions and hydraulic residence time determine whether an aquatic system is volatile or non-volatile relative to atmospheric carbon dioxide equilibrium. First, consider the "non-volatile" system.


^^^^^^^^^^^^^^^^^^^^^
 Non-volatile System}

 For a fixed CT, the molar concentration of each species of the carbonate system is determined by pH. Equations \eqref{ZEqnNum342954}-\eqref{ZEqnNum931548} show these functional relationships.
\begin{equation} \label{ZEqnNum342954}
\left[{\rm H}_{{\rm 2}} {\rm CO}_{{\rm 3}}^{{\rm *}} \right]{\rm \; }={\rm \; }\frac{C_{T} }{1+\frac{K_{1} }{[H^{+} ]} +\frac{K_{1} K_{2} }{[H^{+} ]^{2} } } ={\rm \; }\alpha _{{\rm 0}} C_{T}
\end{equation}
where
\begin{equation} \label{1.4}
\alpha _{{\rm 0}} =\frac{1}{1+\frac{K_{1} }{[H^{+} ]} +\frac{K_{1} K_{2} }{[H^{+} ]^{2} } } {\rm \; }
\end{equation}
\begin{equation} \label{ZEqnNum144714}
\left[{\rm HCO}_{{\rm 3}}^{{\rm -}} \right]={\rm \; }\frac{C_{T} }{\frac{[H^{+} ]}{K_{1} } +1+\frac{K_{2} }{[H^{+} ]} } ={\rm \; }\alpha _{{\rm 1}} C_{T}
\end{equation}
where
\begin{equation} \label{1.6}
\alpha _{{\rm 1}} \; =\; \frac{1}{\frac{[{\rm H} ^{+} ]}{{\rm K} _{1} } +1+\frac{{\rm K} _{2} }{[{\rm H} ^{+} ]} }
\end{equation}
\begin{equation} \label{ZEqnNum944651}
\left[{\rm CO}_{{\rm 3}}^{{\rm -2}} \right]{\rm \; }={\rm \; }\frac{C_{T} }{\frac{[H^{+} ]^{2} }{K_{1} K_{2} } +\frac{[H^{+} ]}{K_{2} } +1} ={\rm \; }\alpha _{{\rm 2}} C_{T}
\end{equation}
where
\begin{equation} \label{ZEqnNum931548}
\alpha _{{\rm 2}} \; =\; \frac{1}{\frac{[{\rm H} ^{+} ]^{2} }{{\rm K} _{1} {\rm K} _{2} } +\frac{[{\rm H} ^{+} ]}{{\rm K} _{2} } +1}
\end{equation}
K1 and placeK2 are the first and second dissociation constants for carbonic acid and ?0, ?1, and ?2 are the fraction of CT in the form ${\rm H}_{{\rm 2}} {\rm CO}_{{\rm 3}}^{{\rm *}} $, ${\rm HCO}_{{\rm 3}}^{{\rm -}} $, and ${\rm CO}_{{\rm 3}}^{{\rm -2}} $ respectively. Because K1 and K2 are constants (K1 = 10-6.3 and placeK2 = 10-10.3), ?0, ?1, and ?2 are only functions of pH.

A measure of the susceptibility of lakes to acidification is the acid neutralizing capacity (ANC) of the lake water. In the case of the carbonate system, the ANC is exhausted when enough acid has been added to convert the carbonate species (${\rm HCO}_{{\rm 3}}^{{\rm -}} $ and ${\rm CO}_{{\rm 3}}^{{\rm -2}} $) to ${\rm H}_{{\rm 2}} {\rm CO}_{{\rm 3}}^{{\rm *}} $. A formal definition of total acid neutralizing capacity is given by equation \eqref{ZEqnNum860037}.
\begin{equation} \label{ZEqnNum860037}
{\rm ANC\; }={\rm \; }\left[{\rm HCO}_{{\rm 3}}^{{\rm -}} \right]+{\rm \; 2}\left[{\rm CO}_{{\rm 3}}^{{\rm -2}} \right]+\left[{\rm OH}^{{\rm -}} \right]{\rm \; -}\left[{\rm H}^{+} \right]
\end{equation}
ANC has units of equivalents per liter. The hydroxide ion concentration can be obtained from the hydrogen ion concentration and the dissociation constant for water Kw.
\begin{equation} \label{ZEqnNum397343}
\left[{\rm OH}^{{\rm -}} \right]{\rm \; }={\rm \; }\frac{K_{w} }{\left[{\rm H}^{+} \right]}
\end{equation}
Substituting equations \eqref{ZEqnNum144714}, \eqref{ZEqnNum944651}, and \eqref{ZEqnNum397343} into equation \eqref{ZEqnNum880414}, we obtain
\begin{equation} \label{ZEqnNum745361}
ANC=C_{T} \left(\alpha _{1} +2\alpha _{2} \right)+{\rm \; }\frac{K_{w} }{\left[{\rm H}^{+} \right]} \; -\left[{\rm H}^{+} \right]
\end{equation}

For the carbonate system, ANC is usually referred to as \textbf{alkalinity}.\footnote{Alkalinity can be expressed as equivalents/L or as mg/L (ppm) of CaCO3. 50,000 mg/L CaCO3 = 1 equivalent/L.}


\paragraph{Volatile Systems: }

 Now consider the case where aqueous ${\rm CO}_{{\rm 2\; aq}} $ is volatile and in equilibrium with atmospheric carbon dioxide. Henry's Law can be used to describe the equilibrium relationship between atmospheric and dissolved carbon dioxide.
\begin{equation} \label{1.12}
\left[{\rm CO}_{{\rm 2\; aq}} \right]={\rm \; P}_{{\rm CO}_{{\rm 2}} {\rm \; }} {\rm K}_{{\rm H}}
\end{equation}
where KH is Henry's constant for CO2 in moles/L-atm and PCO2 is partial pressure of CO2 in the atmosphere (KH = 10-1.5 and PCO2 = 10-3.5). Because $\left[{\rm CO}_{{\rm 2\; aq}} \right]$ is approximately equal to $\left[{\rm H}_{{\rm 2}} {\rm CO}_{{\rm 3}}^{{\rm *}} \right]$ and from equations \eqref{ZEqnNum141302} and \eqref{ZEqnNum944493}
\begin{equation} \label{1.13}
P_{CO_{2} } K_{H} =\alpha _{0} C_{T}
\end{equation}
\begin{equation} \label{ZEqnNum240220}
{\rm C}_{{\rm T}} {\rm \; }={\rm \; }\frac{P_{CO_{2} } K_{H} }{a_{0} }
\end{equation}
Equation \eqref{ZEqnNum240220} gives the equilibrium concentration of carbonate species as a function of pH and the partial pressure of carbon dioxide.

 The acid neutralizing capacity expression for a volatile system can be obtained by combining equations \eqref{ZEqnNum181354} and \eqref{ZEqnNum745361}.
\begin{equation} \label{ZEqnNum755368}
ANC=\frac{P_{CO_{2} } K_{H} }{a_{0} } (\alpha _{1} +2\alpha _{2} )+{\rm \; }\frac{K_{w} }{\left[{\rm H}^{+} \right]} \; -\left[{\rm H}^{+} \right]
\end{equation}



 In both non-volatile and volatile systems, equilibrium pH is controlled by system ANC. Addition or depletion of any ANC component in equation \eqref{ZEqnNum209718} or \eqref{ZEqnNum755368} will result in a pH change. Natural bodies of water are most likely to approach equilibrium with the atmosphere (volatile system) if the hydraulic residence time is long and the body of water is shallow.

PlaceTypeplaceLake PlaceNameANC is a direct reflection of the mineral composition of the watershed. Lake watersheds with hard, insoluble minerals yield lakes with low ANC. Typically watersheds with soluble, calcareous minerals yield lakes with high ANC. ANC of freshwater lakes is generally composed of bicarbonate, carbonate, and sometimes organic matter (${\rm A}_{{\rm org}}^{{\rm -}} $). Organic matter derives from decaying plant matter in the watershed. When organic matter is significant, the ANC becomes (from equations \eqref{ZEqnNum282864} and \eqref{ZEqnNum568463}):
\begin{equation} \label{ZEqnNum466508}
ANC=C_{T} (\alpha _{1} +2\alpha _{2} )+{\rm \; }\frac{K_{w} }{\left[{\rm H}^{+} \right]} \; -\left[{\rm H}^{+} \right]+\left[{\rm A}_{{\rm org}}^{{\rm -}} \right]
\end{equation}
\begin{equation} \label{ZEqnNum217701}
ANC=\frac{P_{CO_{2} } K_{H} }{a_{0} } (\alpha _{1} +2\alpha _{2} )+\frac{K_{w} }{\left[{\rm H}^{+} \right]} \; -\left[{\rm H}^{+} \right]+\left[{\rm A}_{{\rm org}}^{{\rm -}} \right]
\end{equation}
where equation \eqref{ZEqnNum466508} is for a non-volatile system and equation \eqref{ZEqnNum217701} is for a volatile system.

During chemical neutralization of acid, the components of ANC associate with added acid to form protonated molecules. For example:
\begin{equation} \label{1.18}
\left[{\rm H}^{+} \right]{\rm \; }+{\rm \; }\left[{\rm HCO}_{{\rm 3}}^{{\rm -}} \right]{\rm \; }\to \; \left[{\rm H}_{{\rm 2}} {\rm CO}_{{\rm 3}}^{{\rm *}} \right]
\end{equation}
or
\begin{equation} \label{1.19}
\left[{\rm H}^{+} \right]{\rm \; }+{\rm \; }\left[{\rm A}_{{\rm org}}^{{\rm -}} \right]{\rm \; }\to \; \left[{\rm HA}_{{\rm org}} \right]
\end{equation}

In essence, the ANC of a system is a result of the reaction of acid inputs to form associated acids from basic anions that were dissolved in the lake water. The ANC (equation \eqref{ZEqnNum961046}) is consumed as the basic anions are converted to associated acids. This conversion is near completion at low pH (approximately pH 4.5 for the bicarbonate and carbonate components of ANC). Neutralizing capacity to another (probably higher) pH may be more useful for natural aquatic systems. Determination of ANC to a particular pH is fundamentally easy --- simply add and measure the amount of acid required to lower the sample pH from its initial value to the pH of interest. Techniques to measure ANC are described under the procedures section of this lab.

Neutralization of acid precipitation can occur in the watershed or directly in the lake. How much neutralization occurs in the watershed versus the lake is a function of the watershed to lake surface area. Generally, watershed neutralization is dominant. Recently engineered remediation of acid lakes has been accomplished by adding bases such as limestone, lime, or sodium bicarbonate to the watershed or directly to the lakes.


\paragraph{Reactor theory applied to PlaceNameplaceAcid PlaceTypeLake Remediation}

In this experiment sodium bicarbonate will be added to a lake to mitigate the deleterious effect of acid rain. Usually sodium bicarbonate is added in batch doses (as opposed to metering in). The quantity of sodium bicarbonate added depends on how long a treatment is desired, the acceptable pH range and the quantity and pH of the incident rainfall. For purposes of this experiment, a 15-minute design period will be used. That is, we would like to add enough sodium bicarbonate to keep the lake at or above its original pH and alkalinity for a period of 15 minutes (\textit{i.e.}, for one hydraulic residence time).

By dealing with ANC instead of pH as a design parameter, we avoid the issue of whether the system is at equilibrium with atmospheric carbon dioxide. Keep in mind that eventually the lake will come to equilibrium with the atmosphere. In practice, neutralizing agent dosages may have to be adjusted to take into account non-equilibrium conditions.

We must add enough sodium bicarbonate to equal the negative ANC from the acid precipitation input plus the amount of ANC lost by outflow from the lake during the 15-minute design period. Initially (following the dosing of sodium bicarbonate) the pH and ANC will rise, but over the course of 15 minutes, both parameters will drop. Calculation of required sodium bicarbonate dosage requires performing a mass balance on ANC around the lake. This mass balance will assume a completely mixed lake and conservation of ANC. Chemical equilibrium can also be assumed so that the sodium bicarbonate is assumed to react immediately with the incoming acid precipitation. Mass balance on the reactor yields:
\begin{equation} \label{1.20}
Q\left(ANC_{in} \; -\; ANC_{out} \right)\; =\; V\; \; \; \frac{d(ANC)}{dt}
\end{equation}
where:

ANCout = ANC in lake outflow at any time t (for a completely mixed lake the effluent ANC is the same as the ANC in the lake)

ANCin = ANC of acid rain input

V = volume of reactor

Q = acid rain input flow rate.

 If the initial ANC in the lake is designated as ANC0, then the solution to the mass balance differential equation is:
\begin{equation} \label{ZEqnNum453783}
ANC_{out} \; =\; ANC_{in} \; \cdot \; \left(1\; -\; {\mathop{e}\nolimits^{-t/\theta \; \; }} \right)+\; ANC_{0} \; \cdot \; {\mathop{e}\nolimits^{-t/\theta \; }}
\end{equation}
where:

? = V/Q

We want to find ANC0 such that ANCout = 50 �eq/L when t is equal to ?. Solving for ANC0 we get:
\begin{equation} \label{ZEqnNum844648}
{\rm ANC}_{{\rm 0}} {\rm \; }=\left[{\rm ANC}_{{\rm out}} {\rm \; -\; ANC}_{{\rm in}} {\rm \; }\cdot \left(1\; -\; {\mathop{e}\nolimits^{-t/\theta \; \; }} \right)\right]{\mathop{e}\nolimits^{t/\theta \; \; }}
\end{equation}

The ANC of the acid rain (ANCin) can be estimated from its pH. Below pH 6.3 most of the carbonates will be in the form ${\rm H}_{{\rm 2}} {\rm CO}_{{\rm 3}}^{{\rm *}} $ and thus for pH below about 4.3 equation \eqref{ZEqnNum246947} simplifies to
\begin{equation} \label{1.23}
{\rm ANC}\cong -\left[{\rm H}^{+} \right]
\end{equation}
An influent pH of 3.0 implies the ANCin = -$\left[{\rm H}^{+} \right]$ = -0.001 eq/L

Substituting into equation \eqref{ZEqnNum844648}:

 ${\rm ANC}_{{\rm 0}} {\rm \; }=\left[{\rm 0.000050}+{\rm 0.001\; }\cdot \left(1\; -\; {\mathop{e}\nolimits^{-1}} \right)\right]{\mathop{e}\nolimits^{1}} $ = 1.854 meq/L \label{1.24}

The quantity of sodium bicarbonate required can be calculated from:

 [NaHCO3]${}_{0}$ =ANC${}_{0}$ \label{1.25}

 where [NaHCO3]0 = moles of sodium bicarbonate required per liter of lake water
\begin{equation} \label{1.26}
\frac{{\rm 1.854\; mmole\; NaHCO}_{{\rm 3}} }{{\rm liter}} {\rm \times }\frac{{\rm 84\; mg\; NaHCO}_{{\rm 3}} }{{\rm mmole\; NaHCO}_{{\rm 3}} } {\rm \times \; 4\; Liters\; =\; 623\; mg\; NaHCO}_{{\rm 3}}
\end{equation}

------------------
Experimental Objectives}

Remediation of acid lakes involves addition of ANC so that the pH is raised to an acceptable level and maintained at or above this level for some design period. In this experiment sodium bicarbonate (NaHCO3) will be used as the ANC supplement. Since ANC addition usually occurs as a batch addition, the design pH is initially exceeded. ANC dosage is selected so that at the end of the design period pH is at the acceptable level. Care must be taken to avoid excessive initial pH --- high pH can be as deleterious as low pH.

The most common remediation procedure is to apply the neutralizing agent directly to the lake surface, instead of on the watershed. We will follow that practice in this lab experiment. Sodium bicarbonate will be added directly to the surface of the lake that has an initial ANC of 0 �eq/L and is receiving acid rain with a pH of 3. After the sodium bicarbonate is applied, the lake pH and ANC will be monitored for over two approximately 20 minute periods.


------------------
Experimental Apparatus}

The experimental apparatus consists of an acid rain storage reservoir, peristaltic pump, and lake (Figure \eqref{ZEqnNum792377}). The pH of the lake will be monitored using a pH probe connected to a signal-conditioning box that is connected to the laboratory data acquisition system.



 Figure  \label{ZEqnNum792377}. Schematic drawing of the experimental setup.


------------------
Experimental Procedures}

The following directions are written for the use of ProCoDA II hardware and software for pH data collection and manual control of the peristaltic pump. It would also be possible to use automate the experiment and control the pump using the ProCoDA II hardware and software.

We will use a pH probe to measure pH in this experiment. The pH probes are stored in a small plastic box.  Each bench has one pH probe. Plug the pH probe into the blue signal-conditioning box (it takes a push and a twist). Connect the blue cable to one of the sensor ports on your ProCoDA box.

 \begin{enumerate}
\item 1) )Open the ProCoDA II software.

 \item 2) )Navigate to the ``Configuration'' tab and select the ``volts'' button.

 \item 3) )Delete any sensors in the ``Sensor List'' and the insert a new sensor using the ``insert sensor'' button.

 \item 4) )Select the appropriate channel based on in which sensor port you plugged you pH probe.

 \item 5) )Select ``pH Cal.''

 \item 6) )The pH probe should never be dry and is therefore stored with a small vial of pH 4.0 buffer screwed onto the tip.  Unscrew the storage vial cap and place the vial in a place where it will not be tipped over (the cap can stay on the probe).

 \item 7) )Rinse the pH probe with DI water (use a squeeze bottle) into a beaker.

 \item 8) )To calibrate the pH probe, we will use three pH buffer solutions with known pH (red=4.0, yellow=7.0, and blue=10.0).  After rinsing the pH probe, place it into the pH=4.0 buffer.  Stir gently and wait for the pH reading on the software to stabilize.  Once stabilized, press the ``add buffer'' button.  Rinse the pH probe with DI water and repeat for the pH=7.0 and pH=10.0 buffer solutions.

 \item 9) )When you have tested all calibration buffers, hit, ``OK.'' And ``OK'' again.

 \item 10) )Verify that the experimental setup is plumbed so that the ``acid rain'' is pumped directly into the lake.  The lake outflow should discharge into the small drain on the side of your work bench.

 \item 11) )Organize the bench setup so that the metal tube discharging the acid rain into the lake is solidly touching the metal stand that is connected to the stirrer. This will ground the solution that is in the lake and reduce voltage fluctuations that are easily measured by the pH probe.

 \item 12) )Preset pump to give desired flow rate of 267 mL/min (4 L/15 minutes) based on the size of pump tubing selected. Do not turn the pump on yet! For each tubing size, different pump speeds will correspond to different flow rates being output by the pump. The peristaltic tubing sizes are rather arbitrary and are labeled by numbers: 13, 14, 16, 17, and 18 in increasing order of size. If you have \#18 tubing, you will want an RPM setting of (267 mL/min) / (3.8 mL/rev) = 70.3 RPM.
\end{enumerate}



\begin{tabular}{|p{0.4in}|p{0.9in}|p{0.5in}|p{0.5in}|p{0.5in}|p{0.5in}|p{0.5in}|} \hline
 & Tubing Size & 13 & 14 & 16 & 17 & 18 \\ \hline
 & RPM/ID (mm) & 0.8 & 1.6 & 3 & 6.3 & 8 \\ \hline
flow rate in mL/s & 1 & 0.0010 & 0.0035 & 0.0133 & 0.0467 & 0.0633 \\ \hline
 & 50 & 0.0500 & 0.1750 & 0.6667 & 2.3333 & 3.1667 \\ \hline
 & 100 & 0.1000 & 0.3500 & 1.3333 & 4.6667 & 6.3333 \\ \hline
 & mL/rev & 0.06 & 0.21 & 0.80 & 2.8 & 3.8 \\ \hline
\end{tabular}



 \begin{enumerate}
\item 13) )Fill lake with reverse osmosis water and verify that the outflow is set so the lake volume is approximately 4 L.  Place the ``lake'' on top of a magnetic stirrer and add a stir bar.

 \item 14) )Set stirrer speed to 8.

 \item 15) )Add 1 mL of bromocresol green indicator solution to the lake.

 \item 16) )Weigh out 623 mg (not grams!) NaHCO3.

 \item 17) )Add NaHCO3 to the lake.

 \item 18) )After the lake is well stirred take a 100 mL sample from the lake in the plastic sample bottle on your bench.  Don't forget to label the sample bottle (include the time of the sample).

 \item 19) )Clip the pH probe to the side of your lake in a more quiescent zone, away from the influent and effluent.

 \item 20) )We will continuously measure the pH of the effluent and log the data into a spreadsheet format.  In the pH meter software, set the data interval to 1 second.
\end{enumerate}

 Begin logging data to file by clicking on the \includegraphics*[width=0.34in, height=0.34in, keepaspectratio=false]{image2} button. Create a new file in S:{\textbackslash}Courses{\textbackslash}4530{\textbackslash}Group \#{\textbackslash}Lab 2 -- Acid Rain{\textbackslash} with your netids in the name.

 \begin{enumerate}
\item 21) )Prepare to write a comment in the file to mark the time when the pump starts by clicking on the \includegraphics*[width=0.34in, height=0.34in, keepaspectratio=false]{image3} button. Type in a comment and then wait.

 \item 22) )At time equal zero (t=0) start the peristaltic pump and click on the enter button in the comment dialog box.

 \item 23) )Take 100-mL grab samples from the lake effluent at 5, 10, 15, and 20 minutes in the plastic sample bottle on your bench.  Don't forget to label the sample bottle (include the time of the sample). The sample volumes do not need to be measured exactly.

 \item 24) )After the 20-minute sample, measure the flow rate by collecting effluent in a beaker for 30 seconds and measuring the volume collected (in a graduated cylinder for more accurate measurement).

 \item 25) )Turn off the pump and stop measuring pH.

 \item 26) )Measure the lake volume.  This can be done in a large graduated cylinder OR by taking the mass of the water in the lake.  Which would be more accurate?

 \item 27) )Repeat the experiment and change one of the following parameters: stirring, initial ANC, ANC source (use CaCO${}_{3}$ instead of NaHCO${}_{3}$), amount if ANC added.
\end{enumerate}


\paragraph{Analytical Procedures}

\textbf{pH}. pH (-logcitation$\mathrm{\{}$H+$\mathrm{\}}$) is usually measured electrometrically with a pH meter. The pH meter is a null-point potentiometer that measures the potential difference between an indicator electrode and a reference electrode. The two electrodes commonly used for pH measurement are the glass electrode and a reference electrode. The glass electrode is an indicator electrode that develops a potential across a glass membrane as a function of the activity ($\mathrm{\sim}$ molarity) of H+. Combination pH electrodes, in which the H+-sensitive and reference electrodes are combined within a single electrode body will be used in this lab. The reference electrode portion of a combination pH electrode is a [Ag/AgCl/4M KCl] reference. The response (output voltage) of the electrode follows a "Nernstian" behavior with respect to H+ ion activity.
\begin{equation} \label{1.27}
E=E^{0} +\frac{RT}{nF} \ln \left(\frac{\left[H^{+} \right]}{\left[H^{+^{0} } \right]} \right)
\end{equation}
where \textit{R} is the universal gas constant,\textit{ T} is temperature in Kelvin, \textit{n} is the charge of the hydrogen ion, and \textit{F} is the Faraday constant. \textit{E${}^{0}$} is the calibration potential (Volts), and \textit{E} is the potential (Volts) measured by the pH meter between glass and reference electrode. The slope of the response curve is dependent on the temperature of the sample and this effect is normally accounted for with simultaneous temperature measurements.

The electrical potential that is developed between the glass electrode and the reference electrode needs to be correlated with the actual pH of the sample. The pH meter is calibrated with a series of buffer solutions whose pH values encompass the range of intended use. The pH meter is used to adjust the response of the electrode system to ensure a Nernstian response is achieved over the range of the calibration standards.

To measure pH the electrode(s) are submersed in at least 50 mL of a sample. Samples are generally stirred during pH reading to establish homogeneity, to prevent local accumulation of reference electrode filling solution at the interface near the electrode, and to ensure the diffusive boundary layer thickness at the electrode surface is uniform and small.

\textbf{ANC}. The most common method to determine ANC for aqueous samples is titration with a strong acid to an endpoint pH. A pH meter is usually used to determine the endpoint or "equivalence point" of an ANC titration. Determination of the endpoint pH is difficult because it is dependent on the magnitude of the sample ANC. Theoretically this endpoint pH should be the pH where all of the ANC of the system is consumed, but since the ANC is not known \textit{a priori}, a true endpoint cannot be predetermined. However, if most of the ANC is composed of carbonate and bicarbonate this endpoint is approximately pH = 4.5 for a wide range of ANC values.

A 50 to 100-mL sample is usually titrated while slowly stirred by a magnetic stirrer. pH electrodes are ordinarily used to record pH as a function of the volume of strong acid titrant added. The volume of strong acid required to reach the ANC endpoint (pH 4.5) is called the "equivalent volume" and is used in the following equation to compute ANC.
\begin{equation} \label{1.28}
{\rm ANC\; =}\frac{{\rm (equivalent\; vol.)(normality\; of\; titrant)}}{{\rm (vol.\; of\; sample)}}
\end{equation}

A more accurate technique to measure ANC is the Gran plot analysis. This is the subject of next week's analysis. We will directly measure the ANC of the samples that were taken at t=0, 5, 10, 15, and 20 minutes in both of your experiments by means of a Gran plot analysis.


------------------
Pre-Laboratory Questions}

 \begin{enumerate}
\item 1) )How many grams of NaHCO3 would be required to keep the ANC levels in a lake above 50 �eq/L for 3 hydraulic residence times given an influent pH of 3.0 and a lake volume of 4 L, if the current PlaceTypeplacelake PlaceNameANC is 0 �eq/L?
\end{enumerate}


------------------
Data Analysis}

K1 = 10-6.3, placeK2 = 10-10.3, KH = 10-1.5~mol/atm~L, PCO2~=~10-3.5 atm, and Kw = 10-14.

\begin{enumerate}
\item  Plot measured pH of the lake versus dimensionless hydraulic residence time (t/?).

\item  Assuming that the lake can be modeled as a completely mixed flow reactor and that ANC is a conservative parameter, equation 1.21 can be used to calculate the expected ANC in the lake effluent as the experiment proceeds. Graph the expected ANC in the lake effluent versus the hydraulic residence time (t/?) based on the completely mixed flow reactor equation with the plot labeled (in the legend) as ``conservative ANC.''

\item  If we assume that there are no carbonates exchanged with the atmosphere during the experiment, then we can calculate ANC in the lake effluent by using equation 1.11 describing the ANC of a closed system. Calculate the ANC under the assumption of a closed system and plot it on the same graph produced in answering question \#3 with the plot labeled (in the legend) as ``closed ANC.''

\item  If we assume that there is exchange with the atmosphere and that carbonates are at equilibrium with the atmosphere, then we can calculate ANC in the lake effluent by using equation 1.15 describing the ANC of an open system. Calculate the ANC under the assumption of an open system and plot it on the same graph produced in answering question \#3 with the plot labeled (in the legend) as ``open ANC.''

\item  Analyze the data from the 2${}^{nd}$ experiment and graph the data appropriately. What did you learn from the 2${}^{nd}$ experiment?
\end{enumerate}


------------------
Questions}

 \begin{enumerate}
\item 1) )What do you think would happen if enough NaHCO${}_{3}$ were added to the lake to maintain an ANC greater than 50 �eq/L for 3 residence times with the stirrer turned off? How much NaHCO${}_{3}$ would need to be added?

 \item 2) )What are some of the complicating factors you might find in attempting to remediate a lake using CaCO3? Below is a list of issues to consider.

 \item ? �extent of mixing

 \item ? �solubility of CaCO3 (find the solubility and compare with NaHCO${}_{3}$)

 \item ? �density of CaCO3 slurry (find the density of CaCO3)
\end{enumerate}


------------------
References}

 Driscoll, C.T., Jr. and Bisogni, J.J., Jr., "Weak Acid/Base Systems in Dilute Acidified Lakes and Streams of the Adirondack Region of New York State," in \textit{Modeling of Total Acid Precipitation Impacts} J.L. Schnoor (ed.), Butterworth, Stoneham, MA., 53-72 (1983).

 Driscoll, C.T., Baker, J.P., Bisogni, J.J., And Schofield, C.L., "Aluminum Speciation and Equilibria in Dilute Surface Waters of the Adirondack Region of New York State," in \textit{Geological Aspects of Acid Deposition} O.P. Bricker (ed.), Butterworth, Stoneham, MA., 55-75 (1984).

 Barnard. T.E., And Bisogni, J.J., Jr., "Errors in Gran Function Analysis of Titration Data for Dilute Acidified Water," \textit{Water Research}, 19, No. 3 393-399 (1985).

 Bisogni, J.J., Jr. and Barnard, T.E., "Numerical Technique to Correct for Weak Acid Errors in Gran Function Analysis of Titration Data," \textit{Water Research}, 21, No. 10, 1207-1216 (1987).

 Bisogni, J.J., Jr., "Fate of Added Alkalinity During Neutralization of an PlaceNameplaceAcid PlaceTypeLake," \textit{Journal Environmental Engineering}, ASCE, 114, No. 5, 1219-1224 (1988).

 Bisogni, J.J., Jr., and CityplaceKishbaugh, country-regionS.A., "Alkalinity Destruction by Sediment Organic Matter Dissolution During Neutralization of Acidified Lakes," \textit{Water, Air and Soil Pollution}, 39, 85-95 (1988).

 Bisogni, J.J., Jr. and Arroyo, S.L., "The Effect of Carbon Dioxide Equilibrium on pH in PlaceNameplaceDilute PlaceTypeLakes," \textit{Water Research}, 25, No. 2, 185-190 (1991).

 Olem, H. \textit{Liming Acidic Surface Waters}. Lewis Publishers, Chelsea, MI. (1991).

 Stumm, W. and Morgan, J.J., \textit{Aquatic Chemistry}, PersonNameJohn Wiley \& Sons, Inc. NY, NY 1981.


------------------
\eject Lab Prep Notes}

\begin{tabular}{|p{0.7in}|p{0.7in}|p{0.7in}|} \hline
\multicolumn{3}{|p{1in}|}{Table \label{1}. Reagents\newline \textbf{}} \\ \hline
\textbf{Description} & \textbf{Supplier} & \textbf{Catalog number} \\ \hline
HCL 5.0 N & Fisher Scientific & LC15360-2 \\ \hline
H2SO4 5N & Fisher Scientific & LC25840-2 \\ \hline
CaCO3 & Fisher Scientific & C63-3 \\ \hline
Na2CO3 & Fisher Scientific & S263-500 \\ \hline
Buffer-Pac & Fisher Scientific & SB105 \\ \hline
NaHCO3 & Fisher Scientific & S233-500 \\ \hline
Bromocresol Green & Fisher Scientific & B383-5 \\ \hline
ethanol & Fisher Scientific & A962P-4 \\ \hline
\end{tabular}



\begin{tabular}{|p{0.7in}|p{0.7in}|p{0.7in}|} \hline
\multicolumn{3}{|p{1in}|}{Table \label{2}. Equipment list\newline \textbf{}} \\ \hline
\textbf{Description} & \textbf{Supplier} & \textbf{Catalog number} \\ \hline
magnetic stirrer & Fisher Scientific & 11-500-7S \\ \hline
floating stir bar & Fisher Scientific & 14-511-99A \\ \hline
Accumet$\mathrm{{}^{TM}}$ 50 pH meter & Fisher Scientific & 13-635-50 \\ \hline
100-1095 �L pipette & Fisher Scientific & 13-707-5 \\ \hline
10-109.5 �L pipette & Fisher Scientific & 13-707-3 \\ \hline
pH electrode & Fisher Scientific & 13-620-108 \\ \hline
6 L container (lake) & Fisher Scientific & 03-484-22 \\ \hline
Easy load pump head & Cole Parmer & H-07518-00 \\ \hline
digital pump drive & Cole Parmer & H-07523-30\_ \\ \hline
PharMed tubing size 18 & Cole Parmer & H-06485-17 \\ \hline
20 liter HDPE Jerrican & Fisher Scientific & 02-961-50C \\ \hline
\end{tabular}


\paragraph{Bromocresol Green Indicating Solution}

Prepare solution of 400 mg Bromocresol green/100 mL ethanol. Add 0.2 mL of indicator solution per liter of acid rain or lake.


\paragraph{Acid rain}

Acid rain is at pH 3.0. Prepare from distilled water. Add 1 meq H2SO4/L ([H+] at pH 3.0) to obtain a pH of 3.0. To acidify 20 liters of distilled water using 10 N H2SO4:
.. math::


20~L\bullet \frac{1~meq~H2SO4}{L}\bullet \frac{1}{10~N~H2SO4}\bullet \frac{1~N}{1000~meq}=2~mL~of~10~N~H2SO4


\paragraph{Flow Rate}

The residence time of the lake should be 15 minutes. The lake volume is 4 L. thus the flow rate is 267 mL/min. Use \# 18 PharMed tubing.


\paragraph{Setup}

 \begin{enumerate}
\item 1) )Prepare 20-L acid rain for each group.

 \item 2) )Prepare bromocresol green solution if necessary.

 \item 3) )Attach one Easy-Load pump head to the pump drives and plumb with \#18 tubing.

 \item 4) )Plumb Jerrican to pump to lake using quick connectors (see Figure \eqref{ZEqnNum149406}).

 \item 5) )Verify that pH probes are operational, stable, and can be calibrated.

 \item 6) )Verify that buffers (pH = 4, 7, 10) are distributed to each student group.

 \item 7) )Provide a effluent cup in which pH can be measured.
\end{enumerate}


\end{document}
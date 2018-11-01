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





 Measurement of Acid Neutralizing Capacity

 CEE 4530: \textit{Laboratory Research in Environmental Engineering  }Spring, 2018






================
Measurement of Acid Neutralizing Capacity}


------------------
Introduction}

Acid neutralizing capacity (ANC) is a measure of the ability of water to neutralize acid inputs. Lakes with high ANC (such as Cayuga Lake) can maintain a neutral pH even with some acid rain input whereas lakes with an ANC less than the acid input will not maintain a neutral pH. In the Adirondack region of PlaceNameplaceNew York PlaceTypeState, lakes typically receive large inputs of acids during the spring thaw when the accumulated winter snow melts and runs off into the lakes. The ANC of placeAdirondack lakes is not always sufficient to neutralize these inputs.


------------------
Theory}

The ANC for a typical carbonate-containing sample is defined as:
\begin{equation} \label{ZEqnNum434822}
{\rm ANC\; }={\rm \; [HCO}_{{\rm 3}}^{{\rm -}} {\rm ]\; }+{\rm \; 2[CO}_{{\rm 3}}^{{\rm -2}} {\rm ]\; }+{\rm [OH}^{{\rm -}} {\rm ]\; -\; [H}^{+} {\rm ]}
\end{equation}
This equation can be derived from a charge balance if ANC is considered to be the cation contributed by a strong base titrant and if other ions present do not contribute significantly.

Determination of ANC or alkalinity involves determination of an equivalence point. The equivalence point is defined as the point in the titration where titrant volume that has been added equals the "equivalent" volume (Ve). The equivalent volume is defined as:
\begin{equation} \label{1.2}
V_{e} {\rm \; =}\frac{V_{s} \cdot N_{s} }{N_{t} }
\end{equation}
where:

 Ns = normality (in this case alkalinity or ANC) of sample, equivalents/L

 Vs = volume of sample, liters

 Nt = normality of titrant, equivalents/L.



The titration procedure involves incrementally adding known volumes of standardized normality strong acid (or base) to a known volume of unknown normality base (or acid). When enough acid (or base) has been added to equal the amount of base (or acid) in the unknown solution we are at the "equivalence" point. \textit{(Note}: \textit{the point at which we add exactly an equivalent or stoichiometric amount of titrant is the equivalence point. Experimentally, the point at which we estimate to be the equivalence point is called the titration endpoint).}

There are several methods for determining Ve (or the equivalence point pH) from titration data (titrant volume versus pH). The shape of the titration curve (Vt versus pH) can reveal Ve. It can be shown that one inflection point occurs at${\rm V}_{{\rm t}} {\rm \; }={\rm \; V}_{{\rm e}} $. In the case of monoprotic acids, there is only one inflection in the pH range of interest. Therefore, an effective method to find the equivalence volume is to plot the titration curve and find the inflection point. Alternately, plot the first derivative of the titration plot and look for a maximum.


^^^^^^^^^^^^^^^^^^^^^
Gran Plot}

Another method to find the ANC of an unknown solution is the Gran plot technique. When an ANC determination is being made, titration with a strong acid is used to "cancel" the initial ANC so that at the equivalence point the sample ANC is zero. The Gran plot technique is based on the fact that further titration will result in an increase in the number of moles of H+ equal to the number of moles of H+ added. Thus after the equivalence point has been attained, the number of moles of H+ added equals the number of moles of H+ in solution. An equation describing this mass balance is provided as:
\begin{equation} \label{ZEqnNum567204}
N_{t} \left(V_{t} -V_{e} \right)=\left(V_{s} +V_{t} \right)\left[H^{+} \right]
\end{equation}
Solving for the hydrogen ion concentration:
\begin{equation} \label{ZEqnNum183328}
\left[H^{+} \right]=\frac{N_{t} \left(V_{t} -V_{e} \right)}{\left(V_{s} +V_{t} \right)}
\end{equation}
Equation \eqref{ZEqnNum183328} can also be solved directly for the equivalent volume.
\begin{equation} \label{ZEqnNum199885}
V_{e} =V_{t} -\frac{\left[H^{+} \right]\left(V_{s} +V_{t} \right)}{N_{t} }
\end{equation}
Equation \eqref{ZEqnNum199885} is valid if enough titrant has been added to neutralize the ANC. A better measure of the equivalent volume can be obtained by rearranging equation 1.5 so that linear regression on multiple titrant volume - pH data pairs can be used.
\begin{equation} \label{1.6}
\frac{\left(V_{s} +V_{t} \right)}{V_{s} } \left[H^{+} \right]=\frac{N_{t} V_{t} }{V_{s} } -\frac{N_{t} V_{e} }{V_{s} }
\end{equation}
We define F1 (First Gran function) as:

 \includegraphics*[width=3.30in, height=1.96in, keepaspectratio=false]{image1}

 Figure  \label{ZEqnNum245538}. Gran plot from titration of a weak base with 0.05 N acid. CT = 0.001 moles of carbonate and sample volume is 48 mL. The equivalent volume is 4.8 mL. From equation  \eqref{ZEqnNum755200} the ANC is 5 meq/L.
\begin{equation} \label{1.7}
{\rm F}_{{\rm 1}} {\rm \; }={\rm \; }\frac{V_{s} +V_{t} }{V_{s} } {\rm [H}^{+} {\rm ]}
\end{equation}
If F1 is plotted as a function of Vt the result is a straight line with slope = $\frac{N_{t} }{V_{s} } $ and abscissa intercept of Ve (Figure \eqref{ZEqnNum245538}).

The ANC is readily obtained given the equivalent volume. At the equivalence point:
\begin{equation} \label{ZEqnNum665104}
V_{s} \; ANC={\rm \; }V_{e} \; N_{t}
\end{equation}
Equation \eqref{ZEqnNum665104} can be rearranged to obtain ANC as a function of the equivalent volume.
\begin{equation} \label{ZEqnNum755200}
{\rm ANC\; }={\rm \; }\frac{V_{e} \; N_{t} }{V_{s} }
\end{equation}

\paragraph{pH Measurements}

The pH can be measured either as activity (citation$\mathrm{\{}$H+$\mathrm{\}}$ as measured approximately by pH meter) or molar concentration ([H+]). The choice only affects the slope of F1 since [H+] = citation$\mathrm{\{}$H+$\mathrm{\}}$/?.
\begin{equation} \label{1.10}
{\rm F}_{{\rm 1}} {\rm \; }={\rm \; }\frac{V_{s} +V_{t} }{V_{s} } {\rm \; \; [H}^{+} {\rm ]\; }={\rm \; }\frac{V_{s} +V_{t} }{V_{s} } {\rm \; \; }\frac{\{ H^{+} \} }{\gamma } =\; {\rm N} _{t} \frac{V_{t} -V_{e} }{V_{s} }
\end{equation}
where ? is the activity correction factor and the slope is Nt/V0. If H+ concentration is used then
\begin{equation} \label{1.11}
{\rm F}_{{\rm 1}} {\rm \; }={\rm \; }\frac{V_{s} +V_{t} }{V_{s} } {\rm \; \; \{ H}^{+} {\rm \} \; }={\rm \; }\gamma {\rm N}_{{\rm t}} \frac{V_{t} -V_{e} }{V_{s} }
\end{equation}
where the slope is $\frac{\gamma \cdot {\rm N} _{t} }{V_{s} } $.

\textit{(This analysis assumes that the activity correction factor doesn't change appreciably during the titration).}

There are many other Gran functions that can be derived. For example, one can be derived for \textit{Acidity }or the concentration of a single weak or strong acid or base.

To facilitate data generation and subsequent Gran plot construction and analysis pH versus titrant volume can be read directly into a computer, that can be programmed to analyze the data using the Gran plot theory. The program generates the Gran function for all data and then systematically eliminates data until the Gran function (plot) is as linear as possible. The line is then extrapolated to the abscissa to find the equivalent volume.


\paragraph{ANC Determination for Samples with pH $\boldsymbol{\mathrm{<}}$ 4}

After the equivalence point has been reached (adding more acid than ANC = 0) the only significant terms in equation \eqref{ZEqnNum434822} are $\left[{\rm H}^{+} \right]$ and ANC.
\begin{equation} \label{ZEqnNum293697}
\left[{\rm H}^{+} \right]>>{\rm \; }\left[{\rm HCO}_{{\rm 3}}^{{\rm -}} \right]+{\rm \; 2}\left[{\rm CO}_{{\rm 3}}^{{\rm -2}} \right]+\left[{\rm OH}^{{\rm -}} \right]{\rm \; }
\end{equation}
When the pH is 2 pH units or more below the pK${}_{a}$s of the bases in the system the only species contributing significantly to ANC is the hydrogen ion (equation \eqref{ZEqnNum293697}) and thus the ANC is simply
\begin{equation} \label{ZEqnNum542028}
{\rm ANC}={\rm \; -\; [H}^{+} {\rm ]}
\end{equation}
For a sample containing only carbonates, if the pH is below 4 the ANC is approximately equal to -[H+] and no titration is necessary.


\paragraph{Titration Techniques}

Operationally, the first few titrant volumes can be relatively large increments since the important data lies at pH values less than that of the equivalence point (approximately pH = 4.5 for an Alkalinity titration). As the pH is lowered by addition of acid the ionic strength of the solution increases and the activity of the hydrogen ion deviates from the hydrogen ion concentration. This effect is significant below pH 3 and thus the effective linear range is generally between pH 4.5 and pH 3.0. The maximum incremental titrant volume ($\mathrm{\Delta}$Va) that will yield n points in this linear region is obtained as follows.

 If Vs � Vt then equation \eqref{ZEqnNum567204} reduces to
\begin{equation} \label{1.14}
{\rm N}_{{\rm t}} {\rm \; \; \; }\frac{(V_{t} -V_{e} )}{V_{s} } \cong {\rm \; [H}^{+} {\rm ]}
\end{equation}
Let [H+]e be the concentration of hydrogen ions at the equivalence point and [H+]f be the final concentration of hydrogen ions at the end of the titration.
\begin{equation} \label{1.15}
{\rm N}_{{\rm t}} {\rm \; \; \; }\frac{(V_{e} -V_{e} )-(V_{f} -V_{e} )}{V_{s} } ={\rm \; [H}^{+} {\rm ]}_{{\rm e}} {\rm \; -\; [H}^{+} {\rm ]}_{{\rm f}}
\end{equation}
Thus the volume of acid added to go from [H+]e to [H+]f is
\begin{equation} \label{ZEqnNum824828}
{\rm V}_{{\rm f}} {\rm \; -\; V}_{{\rm e}} {\rm \; }={\rm \; }\frac{V_{s} \left([H^{+} ]_{f} -[H^{+} ]_{e} \right)}{N_{t} }
\end{equation}
To obtain n data points between [H+]e - [H+]f requires the incremental titrant volume ($\mathrm{\Delta}$Vt) be 1/n times the volume of acid added between the equivalence point and the final titrant volume. Thus by substituting n$\mathrm{\Delta}$Vt, and typical hydrogen ion concentrations of [H+]e = 10-4.5 and [H+]f = 10-3.0 into equation \eqref{ZEqnNum824828} the maximum incremental titrant volume is obtained.
\begin{equation} \label{1.17}
\Delta {\rm V}_{{\rm t}} {\rm \; }\cong {\rm \; }\frac{(0.001-0.00003)V_{s} }{n\; N_{t} } \cong {\rm \; }\frac{0.001V_{s} }{n\; N_{t} }
\end{equation}

------------------
Procedure}


\paragraph{Determine ANC of Acid Rain Samples}

Determine the ANC for all samples collected from the Acid Lake Remediation lab.  Start with 50 mL from the t=0 sample and run through the procedure to learn how the software works. Then repeat the procedure with 50 mL from the t=0 sample and for remaining samples with the goal of making an accurate ANC measurement and creating an accurate titration curve by using 0.100 mL titrant increments throughout the entire titration. Remember that the biggest source of error for this lab will likely be poor pipette techniques.

 \begin{enumerate}
\item 1) )Measure 50 mL of an acid lake sample in a graduated cylinder.

 \item 2) )Add to a 100 mL beaker.

 \item 3) )Place the beaker on the magnetic stirrer, add a stir bar and stir slowly.

 \item 4) )Place the pH electrode in the solution.

 \item 5) )If the initial pH is less than 4.5 no titration is necessary and equation \eqref{ZEqnNum542028} can be used to calculate the ANC.

 \item 6) )Record the initial pH (prior to adding any titrant) and initial sample volume.

 \item 7) )Analyze the sample using Gran plot analysis as detailed in Appendix 4A.  Add 0.05 N HCl (the titrant) using a digital pipette in increments of 0.100 mL.

 \item 8) )Save the Gran data to S:{\textbackslash}Courses{\textbackslash}4530{\textbackslash}Group \#{\textbackslash}Lab 2 -- Acid{\textbackslash}group\#\_gran
\end{enumerate}

 by selecting \includegraphics*[width=0.34in, height=0.34in, keepaspectratio=false]{image2}. The data will be saved in a file (tab delimited format) that can be opened by any spreadsheet program. You will use this data to plot a titration curve and to verify that the Gran technique accurately measures the ANC of a sample.

 \begin{enumerate}
\item 9) )Record the ANC and the equivalent volume.
\end{enumerate}

 If the error is greater than 2\% then check your pipette technique using a balance and then repeat the titration.


------------------
Prelab Questions}

 \begin{enumerate}
\item 1) )Compare the ability of Cayuga lake and Wolf pond (an placeAdirondack lake) to withstand an acid rain runoff event (from snow melt) that results in 20\% of the original lake water being replaced by acid rain. The acid rain has a pH of 3.5 and is in equilibrium with the atmosphere. The ANC of Cayuga lake is 1.6 meq/L and the ANC of Wolf Pond is 70 �eq/L. Assume that carbonate species are the primary component of ANC in both lakes, and that they are in equilibrium with the atmosphere. What is the pH of both bodies of water after the acid rain input? Remember that ANC is the conservative parameter (not pH!). \textit{Hint: You can use the scipy optimize root finding function called brentq. Scipy can't handle units so the units must be removed using .magnitude.}

 \item 2) )What is the ANC of a water sample containing only carbonates and a strong acid that is at pH 3.2? This requires that you inspect all of the species in the ANC equation and determine which species are important.

 \item 3) )Why is [H+] not a conserved species?
\end{enumerate}


------------------
Questions}

 \begin{enumerate}
\item 1) )Plot the titration curve of the t=0 sample with 0.05 N HCl (plot pH as a function of titrant volume). Label the equivalent volume of titrant. Label the 2 regions of the graph where pH changes slowly with the dominant reaction that is occurring. (Place labels with the chemical reactions on the graph in the pH regions where each reaction is occurring.) Note that in a third region of slow pH change no significant reactions are occurring (added hydrogen ions contribute directly to change in pH).

 \item 2) )Prepare a Gran plot using the data from the titration curve of the t=0 sample. Use linear regression on the linear region or simply draw a straight line through the linear region of the curve to identify the equivalent volume. Compare your calculation of Ve with that was calculated by ProCoDA.

 \item 3) )Plot the measured ANC of the lake on the same graph as was used to plot the conservative, volatile, and nonvolatile ANC models (see questions 2 to 5 of the Acid Precipitation and Remediation of an Acid Lake lab). Did the measured ANC values agree with the conservative ANC model?
\end{enumerate}


------------------
References}

 Sawyer, C.N., P.L. McCarty and G.F. Parkin \textit{Chemistry for Environmental Engineering}\underbar{, }4th ed., McGraw-Hill (1994).

 Pankow, J.F. \textit{Aquatic Chemistry Concepts}, Lewis Publishers (1991).

 Morel, F.M.M. and J.G. Hering \textit{Principles and Applications of Aquatic Chemistry} Wiley-Interscience (1993).

 Stumm, W. and J.J. Morgan \textit{Aquatic Chemistry} 2nd ed. Wiley Interscience (1981).


------------------
\eject Lab Prep Notes}

 Table \label{1}. Reagent list.

\begin{tabular}{|p{0.7in}|p{0.7in}|p{0.7in}|} \hline
\textbf{Description} & \textbf{Supplier} & \textbf{Catalog number} \\ \hline
HCl 5.0 N & Fisher Scientific & LC15360-2 \\ \hline
Buffer-Pac & Fisher Scientific & SB105 \\ \hline
 &  &  \\ \hline
\end{tabular}

Table \label{2}. Equipment list

\begin{tabular}{|p{0.7in}|p{0.7in}|p{0.7in}|} \hline
\textbf{Description} & \textbf{Supplier} & \textbf{Catalog number} \\ \hline
Accumet$\mathrm{{}^{TM}}$ 50 pH meter & Fisher Scientific & 13-635-50 \\ \hline
 pH electrode & Fisher Scientific & 13-620-108 \\ \hline
7x7 stirrer & Fisher Scientific & 11-500-7S \\ \hline
stirbar 1/2" long & Fisher Scientific & 14-511-62 \\ \hline
100 mL Fisher beaker & Fisher Scientific & 02-593-50B \\ \hline
\end{tabular}


\paragraph{Setup}

 \begin{enumerate}
\item 1) )Verify that the pH probes are operational, stable, and can be calibrated.

 \item 2) )Verify that buffers (pH = 4, 7, 10) are distributed to each student group
\end{enumerate}

\eject


================
Appendix 4A -- Using the Gran Plot software}


------------------
Gran Plot}

\begin{enumerate}
\item \textbf{ }Open the ProCoDA II software in the ProCoDA II folder on the desktop.

\item  Connect and calibrate your pH probe as you did in the Acid Precipitation laboratory.

\item   The Gran technique is used to measure acid or base neutralizing capacity.  To begin a Gran analysis, navigate to configuration, select volts, select pH cal, and click on \includegraphics*[width=0.34in, height=0.34in, keepaspectratio=false]{image3}.

\item  You will be prompted for the ``normality of titrant'' and the ``volume of sample''.  You can also choose to measure ANC (acid neutralizing capacity) or BNC (base neutralizing capacity). If you are measuring BNC you will need to titrate with a strong base. After entering the normality of acid (or base) and the sample volume the computer will suggest an incremental volume of titrant that will produce a good Gran plot. Smaller incremental titrant volumes can be used, but will require more time to titrate the sample. After entering the values, exit the dialog box by clicking on the OK button. It will look like this:
\end{enumerate}



\includegraphics*[width=2.74in, height=1.99in, keepaspectratio=false]{image4}



\begin{enumerate}
\item  The Gran Plot analysis uses 3 controls: \includegraphics*[width=1.04in, height=0.66in, keepaspectratio=false]{image5}, \includegraphics*[width=0.96in, height=0.21in, keepaspectratio=false]{image6}, and \includegraphics*[width=1.01in, height=0.21in, keepaspectratio=false]{image7}. The "incremental titrant added" is the amount of acid added since the previous time the \includegraphics*[width=0.96in, height=0.21in, keepaspectratio=false]{image8} button was clicked. For the first data point if no titrant was added the "incremental titrant added" should be set to zero. For subsequent readings, change the incremental titrant added to the volume you are adding, add the titrant with a digital pipette, wait for the pH to stabilize and then click on \includegraphics*[width=0.96in, height=0.21in, keepaspectratio=false]{image9}. Any amount of titrant can be added at each step, but it is important that below pH 5 the titrant volumes be smaller than the recommended value so that sufficient data points are obtained in the linear region.

\item  There is no way to delete unwanted data points after they are accepted. Therefore, make sure you only press the enter button once after each addition of titrant.
\end{enumerate}

\eject

\begin{enumerate}
\item  Continue adding titrant until a line is fit through the linear region of the data. When the line is drawn through the linear region press \includegraphics*[width=1.01in, height=0.21in, keepaspectratio=false]{image10}. Note that \includegraphics*[width=1.01in, height=0.21in, keepaspectratio=false]{image11} accepts the last data point and ends the titration. \includegraphics*[width=1.01in, height=0.21in, keepaspectratio=false]{image12} is pressed after the last addition of acid INSTEAD of pressing \includegraphics*[width=0.96in, height=0.21in, keepaspectratio=false]{image13}!

\item  The equivalent volume (V${}_{e}$) is given in the same units as were used for the titrant and sample volumes. The equivalent volume is the abscissa intercept of the line fit to the data in the region of constant slope. The ANC is given in equivalents per liter.

\item  If desired the titration data can be saved in a format that can be read by spreadsheet programs by selecting  \includegraphics*[width=0.34in, height=0.34in, keepaspectratio=false]{image14}. You will be prompted for a file name and location.
\end{enumerate}






\end{document}
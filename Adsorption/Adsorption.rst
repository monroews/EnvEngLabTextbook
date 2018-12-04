
.. _title_Adsorption:

*****************
Adsorption
*****************

Water is sometimes called the universal solvent and that property has both positive and negative aspects. On the positive side, water's ability to serve as a carrier for many compounds is essential for life. On the negative side that same ability can result in water carrying substances that are harmful to life. Environmental engineers often have the challenge of removing harmful dissolved species from water. This task shows up when we are producing safe drinking water from a ground water source that is contaminated with arsenic, fluoride, nitrate, or atrazine. Surface water sources can be contaminated with naturally organic matter that interacts with disinfectants to produce toxic by products. Wastewater reuse requires removal of a long list of dissolved species that would otherwise accumulate. Dyeing of clothing produces an industrial waste water contaminated with high concentrations of dissolved dyes. As we develop improved analytical techniques we realize that many of the substances that we use including caffeine, cocaine, pharmaceuticals, herbicides, and pesticides are present in the environment.

Our strategies for removing dissolved species are limited to stopping the manufacture and use of the harmful compounds, encouraging reactions to transform the compounds into less harmful products, or removing the compounds from water. Of course, removing the compounds from water requires that we put the compounds somewhere else. We can either concentrate the compounds in water (reverse osmosis) or transfer the compounds into a gas (air stripping) or solid phase (adsorption).

Adsorption to a solid phase is commonly used in drinking water treatment plants. Aluminum and iron hydroxide coagulant nanoparticles are used for flocculation because they are sticky and readily attach to suspended particles. The coagulant nanoparticles also adsorb many dissolves species including naturally occurring dissolved organics. The coagulant nanoparticles are then concentrated in the solid phase of the sludge produced by water treatment plants. Activated carbon is also used in drinking water treatment to transfer dissolved species to the solid phase. This laboratory experiment will give us an opportunity to learn about the removal of dissolved species through adsorption to a solid phase.


.. _heading_Adsorption_Objectives:

Objectives
==========

The objectives of this experiment are to:


 #. Investigate the breakthrough characteristics of red dye \#40 on activated carbon or on coagulant nanoparticles in a continuous-flow carbon contactor at a range of concentrations.
 #. Determine the equilibrium partitioning of red dye \#40 on activated carbon or on coagulant nanoparticles

.. _heading_Adsorption_Background:

Background
==========

Adsorption is a unit operation in which surface-active materials in true solution are removed from the solvent by interphase transfer to the surface of an adsorbent particle. This process is employed in environmental engineering practice for removal of various pollutants such as soluble organics, dyes, pesticides, humic substances, etc., from wastewaters and for removal of color, taste, and odor-producing compounds from natural waters that are to be used as potable water supplies. Adsorption onto granular activated carbon (GAC) also finds wide application in the remediation of groundwater contaminated with volatile and nonvolatile organic pollutants.

Under isothermal conditions the equilibrium partitioning between solution and solid phase is a function of concentration. In this experiment the partitioning will be analyzed using both Freundlich

.. math::
    :label: Freundlich

    q =K_f C^{\frac{1}{n}}

and Langmuir partitioning models

.. math::
    :label: Langmuir

   q =\frac{K_{Lang}q_{\max} C}{1+K_{Lang}C}

 | Where
 | :math:`q` is the mass of adsorbate (species being removed from solution) per mass of adsorbent (solid phase)
 | :math:`C` is the concentration of the adsorbate in water
 | :math:`K_f` and :math:`n` are the Freundlich empirical constants describing the partitioning
 | :math:`K_{Lang}`and :math:`q_{\max}` are the Langmuir empirical constants describing the partitioning

We will preload columns of sand (or glass beads) with the adsorbent and then pump a solution of red dye \#40 through the column. We will measure the effluent concentration of the dye as a function of time using a photometer. In these experiments the column of sand is inert, but provides a mechanism to hold the adsorbent stationary (fixed bed) while the red dye solution flows through. The red dye will adsorb to the adsorbent and the effluent red dye concentration is expected to be very low for some time. Red dye will begin breaking through once the majority of the adsorbent reaches equilibrium with the influent concentration of the red dye.

In this analysis we are neglecting several aspects of the adsorption process. We assume that the time required to reach equilibrium partitioning is very small relative to the hydraulic residence time (:math:`\theta_{HRT}` ) of the column. This assumption requires that both liquid phase and solid phase adsorbate mass transport mechanisms are relatively fast. Transport within the solid phase matrix is by the slow process of diffusion. Thus we expect diffusion to increase the time required to reach equilibrium for adsorbents that require diffusion over longer distances. Diffusion time will be greatest for Large diameter granular activated carbon, less for powdered activated carbon, and very fast for coagulant nanoparticles.

The mass of the adsorbate in the column per plan view area at breakthrough is given by

.. math::

    M_{dye} = M_{adsorbent} q_{0}
    v_mtz =  C_0 V_a t *A

 | where
 | :math:`M_{AC}` and :math:`M_{GAC}` are the masses of the adsorbents per plan view surface area of the column
 | :math:`v_a` is the approach velocity of the water above the sand bed
 | :math:`\phi` is the porosity of the sand bed
 | :math:`L` is the depth of the sand bed
 | :math:`C_0` is the influent concentration of the adsorbate (red dye \#40)

The mass transfer zone travels at velocity :math:`v_{mtz}` through the fixed bed as the absorbent slowly fills to the equilibrium density, :math:`q_0`, based on the influent concentration, :math:`C_0`.

.. _figure_mass_transport_zone:

.. figure:: Images/mtz.png
    :target: https://youtu.be/ziLug9EEwM4
    :width: 400px
    :align: center

    Movie illustrating how the effluent concentration of the absorbate changes with time as the mass transfer zone moves through the fixed bed.

The velocity of the mass transfer zone (mtz or the adsorption front) can be obtained by a mass balance on the system. If we set our frame of reference (and our control volume) to be centered on the mass transfer zone, then the average velocity (over the pore fraction of the control surface) of fluid entering the mtz is equal to pore water velocity minus the velocity of the mtz. The fluid phase concentration of the adsorbate entering the control surface is :math:`C_0` and the fraction of the control surface where fluid is passing through is the porosity, :math:`\phi`.

The average velocity of the solid phase exiting through the control surface is :math:`-v_{mtz}`. The bulk density of the adsorbate is :math:`q_0 \rho_{bulk \; adsorbent}` where :math:`\rho_{bulk \; adsorbent}` is the mass of adsorbent per volume of the packed bed. The mass rate of adsorbate passing through the control surface in liquid phase must precisely balance the mass rate of adsorbate passing through the control surface in the solid phase because the mtz is stationary.

.. math::

    [(v_{pore} - v_{mtz})C_0\phi] - [(v_{mtz})q_0 \rho_{bulk \; adsorbent}] = 0

We can apply continuity to find the relationship between the velocity in the pores and velocity above the porous fixed bed. The plan view area of the fixed bed cancels out.

.. math::

    \phi v_{pore} = v_a

Eliminate :math:`v_{pore}` from the equation

.. math::

    (v_a C_0 - v_{mtz}C_0\phi) - [(v_{mtz})q_0 \rho_{bulk \; adsorbent}] = 0



Now solve for :math:`v_{mtz}`.

.. math::
    :label: eq_Adsorb_v_mtz

    v_{mtz}=\frac{v_a C_0}{C_0\phi + q_0 \rho_{bulk \; adsorbent}}

In equation :refnum:`eq_Adsorb_v_mtz` the term :math:`C_0\phi` represents the liquid phase mass of the adsorbate per unit volume of the fixed bed and the term :math:`q_0 \rho_{bulk \; adsorbent}` represents the solid phase mass of the adsorbate per unit volume of the fixed bed. The second term dominates for fixed bed adsorption reactors that are effective and thus equation :refnum:`eq_Adsorb_v_mtz` simplifies to:

.. math::
    :label: eq_Adsorb_v_mtz_simple

    v_{mtz} \cong \frac{v_a C_0}{q_0 \rho_{bulk \; adsorbent}}

The time until breakthrough can be obtained by dividing the length of the adsorption column (:math:`L_column`) by the velocity of the mtz (equation :refnum:`eq_Adsorb_v_mtz`)

.. math::
    :label:

     \frac{L_{column}}{v_{mtz}} = \frac{L_{column}\phi}{v_a} + \frac{L_{column}q_0 \rho_{bulk \; adsorbent}}{v_a C_0}

     t_{mtz} = t_{water} + t_{ads}

Thus the time to breakthrough is the time required for water to flow through the reactor plus the additional time required due to the adsorption process. The retardation factor is defined as the ratio of the time for the mass transfer zone to travel through the bed divided by the time for water to travel through the bed.

.. math::

    R_{adsorption} = \frac{t_{mtz}}{t_{water}} = \frac{v_{water}}{v_{mtz}}

    R_{adsorption}\cong  \frac{v_a q_0 \rho_{bulk \; adsorbent}}{\phi v_a C_0} =\frac{q_0 \rho_{bulk \; adsorbent}}{\phi C_0}

The effective bed porosity, :math:`\phi` can be calculated from

.. math::

    \phi =1-\frac{\rho _b }{\rho _{ac} }

where

 | :math:`\rho_b =` apparent bulk density
 | :math:`\rho_{ac}  =  2.1 g/cm^3`

From experiments conducted in the Cornell environmental laboratory around 2003 we have  q_{50 mg/L} = 0.08. Our goal is to design a fixed bed reactor that has a :math:`t_{mtz}` of about 30 minutes. With a 15 cm deep column at 1 mm/s and with a porosity of 0.4 the hydraulic residence time is 1 minute. Given a target retardation factor of 30 we can calculate the bulk density of carbon that we should have in the column. We can achieve this bulk density by

.. math::

    \rho_{bulk \; adsorbent} \cong \frac{R_{adsorption}\phi C_0}{q_0}

Different teams can try different concentrations of red dye or different masses of activated carbon.

.. code:: python

   """ importing """
   from aide_design.play import*
   v_a = 1 * u.mm/u.s
   porosity = 0.4
   L_column = 10 * u.cm
   C_0 = 50 * u.mg/u.L
   q_0 = 0.08
   t_water = (L_column*porosity/v_a).to(u.s)
   t_mtz = 1800*u.s
   # set the breakthrough time to 30 minutes = 1800 s
   R_adsorption = t_mtz/t_water
   Density_bulk = (R_adsorption * porosity * C_0/q_0).to(u.kg/u.m**3)
   Density_bulk
   D_column = 1*u.inch
   A_column = pc.area_circle(D_column)
   V_column = A_column * L_column
   M_carbon = (V_column * Density_bulk).to(u.mg)
   M_carbon
   V_reddye = (v_a*A_column*t_mtz).to(u.L)
   V_reddye
   Q_reddye = (v_a*A_column).to(u.mL/u.min)
   Q_reddye
   density_sand = 2650 * u.kg/u.m**3
   M_sand = (V_column*density_sand*(1-porosity)).to(u.g)
   M_sand





The Freundlich parameters K and n can be fit using a power law relationship and Langmuir parameters K and :math:`q_{\max }^{\star}` can be fit using nonlinear regression.




.. _heading_Adsorption_Contactor_Procedures:

Contactor Procedures
====================

.. _figure_AC_Schematic:

.. figure:: Images/Schematic.png
    :width: 500px
    :align: center
    :alt: internal figure

    Proposed design of the carbon column and feed system.

Continuous-Flow Carbon Contactor Setup (week 1)
-----------------------------------------------


Assemble the system shown in :numref:`figure_AC_Schematic`. Use a peristaltic pump with \#14 tubing at approximately 10 rpm. Prepare 20 L jerricans with 50 mg/L of Red dye \#40. Use reverse osmosis water to dilute the dye. The carbon contactor will be operated in down flow mode. The specifications for the carbon contactors are given in Table :numref:`table_carbon_contactor_settings`.

.. _table_carbon_contactor_settings:

.. csv-table:: Carbon contactor settings.
   :header: Parameter,	Value
   :widths: 20, 20
   :align: center

    Influent red dye Concentration,        0.050  g/L
    Depth of fixed bed, 15 cm
    Influent flow rate, 30 ml/min
    Column diameter, 2.5 cm
    Carbon bulk density, 0.375 :math:`g/cm^3`
    Mass of carbon, 570 mg
    Mass of sand (to obtain 15 cm)
    q, 0.080  g/g
    Mass of red dye/20 L, 1.00 g
    Mass of sand, 80 g

Set up the Contactor
--------------------

 #. Test column and pump and all tubing to ensure that it is leak tight using reverse osmosis water.
 #. Remove top from column
 #. Mix 80 g of sand and 570 mg of activated carbon
 #. Pour mixture of sand and activated carbon into a beaker containing reverse osmosis water.
 #. Swirl until most of the air is released.
 #. Use a funnel and a reverse osmosis water wash bottle to wash the mixture from the beaker into the column.
 #. Use a 50 mL syringe to remove excess water from the top of the column if necessary.
 #. Use a long rod to gently stir activated carbon to help release air bubbles.
 #. Assemble the column end fitting.
 #. In up flow mode (at 30 mL/min), discharge the column effluent to waste until most of the fines are removed.
 #. Reverse the direction of flow to down flow.
 #. Configure ProCoDA to log the concentration of red dye at 5 second intervals

Operate the Contactor
---------------------

 #. Start pumping Red Dye \#40.
 #. Measure the flow rate using a balance to get mass of water in approximately 1 minute.
 #. It is impractical to try and achieve :math:`C/C_0 = 1`, but run long enough to attain at least :math:`C/C_0 = 0.8`.



Isotherm Results and Discussion
-------------------------------

Combine the data from all groups when doing the following analysis.

 #. Calculate the quantity of Red Dye \#40 that was transferred to the surface of the activated carbon for each bottle in grams/gram of GAC.
 #. Plot the data in a standard adsorption isotherm format (i.e., quantity sorbed, g/g, versus aqueous concentration, g/L).
 #. Attempt to fit both the Freundlich and Langmuir isotherm models to the data. Report the values of the respective constants in each case, and plot the fitted model curves on the same graph as the data. (Remember to use smooth lines for models and data points for data.) Use nonlinear regression to obtain the Langmuir isotherm parameters.
 #. Discuss the correspondence between the experimental data and the Freundlich and Langmuir isotherms.

Contactor Results and Analysis
------------------------------

 #. Plot the breakthrough curve showing :math:`\frac{C}{C_0}` versus time or :math:`\frac{C}{C_0}` versus cumulative volume treated. [Note: Obviously, if flow rate were held relatively constant, then volume treated and time are directly proportional, and either can be effectively plotted on the abscissa. However, if flow rate was not constant, it is preferable to plot :math:`\frac{C}{C_0}` versus cumulative volume treated, as the volume treated by the midpoint of breakthrough should be relatively independent of flow rate. Where flow rate was not constant, the cumulative volume treated can be estimated by summing the incremental volumes delivered during each interval between samplings, assuming average values for the interval flows.]
 #. From knowledge of both the mass of GAC added and the measured volume of the GAC bed, estimate the apparent bulk density (:math:`\rho_b`) of the bed during operation. Assuming a real (carbon) density of 2.1 :math:`g/cm^3`, estimate the effective bed porosity (:math:`\phi`).
 #. Calculate the expected breakthrough time (or volume treated) --- i.e., ignoring mass-transfer limitations --- based on your isotherm, flow and other data. Compare the actual breakthrough time (or volume treated), approximately the point where C/C0 = 0.5, with its expected value and offer explanations for discrepancy.
 #. Attempt to model the shape of your breakthrough-curve data, using the mass-transfer model presented in lecture:


[Note that the generalized isotherm is described by specifying one point on it (:math:`C_0`, Q) and corresponding value for a curve parameter (r). Alternative choices of :math:`C_0` will yield corresponding --- but different --- sets of Q and r-values that result in identical generalized isotherm curves. Therefore, the proper choice of :math:`C_0` for convenient, later application to breakthrough-curve modeling would be the average measured value of the column's influent Red Dye \#40 concentration --- and not the initial Red Dye \#40 concentration employed in the isotherm determination. That way, the values of Q and r obtained will be the correct ones to employ in the mass-transfer model.]

Alternatively, note that the Langmuir isotherm fit can be conveniently employed. The Langmuir is a special case of the generalized isotherm, where :math:`r=\frac{1}{1+KC_{0} }` (with K being the Langmuir constant). Q can be estimated from the Langmuir isotherm by substituting the column's influent Red Dye \#40 concentration for :math:`C_0`.

What value of k', the effective mass-transfer coefficient, gives best fit to the shape of your breakthrough curve? [Note: If the observed midpoint of breakthrough was significantly displaced in time (or volume treated) from that predicted from your isotherm, you should use your experimentally observed S value, rather than the theoretically predicted one. That way, you'll only have to deal with effects of k' on shape, rather than absolute position, of breakthrough.] If we had generated breakthrough curves at several values of hydraulic loading, we could empirically relate :math:`k'` to hydraulic loading for evaluating design and operating alternatives.


 #. Provide the usual discussion of error sources and suggestions for improvement.


.. _heading_Adsorption_Lab_Prep_Notes:

Lab Prep Notes
==============


.. _table_Activated_carbon_reagent_list:

.. csv-table:: Reagent list.
    :header: Description,	Supplier,	Catalog number
    :widths: 20, 20, 10
    :align: center

    activated carbon,	,
    red dye \#40, ,


 #. Verify that all necessary supplies are in place for the pumps, tanks, column, valves, and tubing.
 #. Prepare the Red Dye \#40 stock solution.
 #. Prepare a 5\% bleach solution (5 mL bleach diluted to 100 mL with distilled water) for cleaning the photometer sample cell and sample lines.

Procedure to remove air from the top of the column
--------------------------------------------------

 #. Close the Red Dye \#40 influent valve.
 #. Open the distilled water influent valve.
 #. Wait for the influent line to clear of Red Dye \#40.
 #. Turn off the pump.
 #. Reverse the column flow direction.
 #. Turn on the pump until the air is removed.
 #. Turn off the pump.
 #. Reverse the column flow direction.
 #. Turn on the pump and switch the influent to Red Dye \#40.

.. _heading_Adsorption_Recommendations_from_previous_years:

Recommendations from previous years
===================================

The column that was run at the slower flow rate had a much steeper breakthrough curve. However, it took 2 weeks to breakthrough. Thus it is recommended that a shorter column be used (15 cm rather than 60 cm) so that the breakthrough occurs in a reasonable amount of time with a slower flow rate.

Methylene blue may not be an ideal contaminant since it is a stain that absorbs strongly. It may be preferable to use red dye \#40.

We used red dye \#40 and obtained similar results. The problem with this lab is that mass transfer of solute into the activated carbon pores is rate limiting and the rate decreases as the pores fill. We used 100 mg of activated carbon in all isotherm bottles and varied the red dye concentration from 500, 250, 100, 75, to 50 mg/L. The range between 100 and 50 mg/L should be divided further for more data. Samples below 50 mg/L were clear.

The turbidity standard helps, but the spectrophotometer does pick up adsorbed red dye with a slightly different spectra than dissolved red dye. The best approach would be to filter the samples to remove the activated carbon fines.

We used red dye standards of 500, 150, 50, 15, 5, 1.5, 0.5 mg/L. We used a red dye stock containing 10 g/L.

Decreased flow rate in column to 15 mL/min.

References
==========

Lawler, D. F., & Benjamin, M. M. (2013). Water quality engineering: physical / chemical treatment processes. Hoboken, N.J.: Wiley. Retrieved from http://search.ebscohost.com/login.aspx?direct=true&scope=site&db=nlebk&db=nlabk&AN=631668

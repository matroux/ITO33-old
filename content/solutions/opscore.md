---
title: Opscore
image: "/images/solutions.jpg"
topInfo:
  enable: true
  type: breadcrumb
  bg: dark
  list:
  - text: Solutions
    link: "/solutions/"
  - text: Opscore
    link: "#"
widgets:
  before:
    - enable: true
      type: solutions
      title: >-
        The Convertible Bond Pricing Solution   
      subtitle: A complete front-office solution for the pricing, hedging and analysis 
    - enable: true
      class: pt-5 c0l-12  bg-half mb-5
      type: banner
      layout: 
      title: RAVINTOLA JOKAISEEN MAKUUN
      bannerItem:
      - bg_image: images/backgrounds/about-us-bg.webp
        content: >-
         <i class="fa fa-check"></i> DATA MODEL OF TERMS AND CONDITIONS    


         <i class="fa fa-check"></i> PRICING ENGINE   


         <i class="fa fa-check"></i> EXCEL FRONT END       
        image: images/Cocobanking.jpg
        subtitle: ''
        title: ' Opscore consists of three components:'
        button:
          enable: "true"
          label: "Request a Demo"
          popup: "true"
          link: "#requestdemo"
    - enable: true
      type: accordian
      lists:
      - title: DATA MODEL OF TERMS AND CONDITIONS
        subtitle: 'Opscore'
        content: >-
         Opscore is our complete front-office solution for the pricing, hedging and analysis of convertible securities. According to Sheen Kassouf and Edward Thorp              (co-authors of Beat the Market), a convertible security is “any security that may be exchanged for common stock”. In addition to warrants, Kassouf and Thorp's            classification includes convertible bonds, convertible preferred stocks, calls, stock rights and stock options. Opscore consists of three components:

           The clauses of convertible securities can be so complex that their accurate treatment not only necessitates pricing engines as evolved as ours, but also                 requires referring to the prospectus as the only reliable and complete source of information.

            For this reason, we maintain a continuously evolving database schema for the terms and conditions of convertible securities. Each time we add a new feature             to our pricing engine (after some newly released prospectus), we release the updates of both the pricing engine and the data model.

            Terms and conditions can be edited through a graphical user interface, as shown in Figure 1, and stored in the database. The user can also create and                   define terms and conditions for new issues of convertible securities.

            The data model of Opscore covers convertible bonds, mandatories, equity options and CB callable asset swaps as shown in Figure 2. Terms and conditions of               credit default swaps (CDS) are also handled, as they are needed for the calibration of the default component of the equity-to-credit process.
        button:
          enable: ""
          label: "Request a Demo" 
          link: ""
      - title: PRICING ENGINE
        subtitle: ''
        content: >-
         This is the heart of Opscore and the core of our expertise. The pricing engine is the numerical solver of the equity-to-credit Partial Differential Equations           (PDE) with the terms and conditions of the given derivative instrument acting as boundary conditions. Our implementation relies on the most advanced finite              difference schemes. These schemes include computational grids that adapt in order to best capture the events, whether in time or space, that occur during              the lifetime of the specific instrument.

            Inputs to the pricing engine are the terms and conditions of the instruments involved in the pricing, market data (yield curves, stock spot price and FX               rates), market assumptions (dividend forecast and recovery rates for each instrument involved on pricing and calibration) and the theoretical parameters               (Brownian volatility, hazard rate) which are inferred from the calibration routines, themselves an integral part of the pricing engine.

            Programmed in C++, the pricing engine can be exploited as a separate suite of DLLs (Dynamic-Link Libraries) which the user may wish to integrate into                    his/her exisiting system, independently of the database schema of Opscore or the Excel functionality. To this end, COM, Java and C++ interfaces are                    available. The DLL can also be called from Matlab. The client, therefore, can choose between integrating our DLLs into his/her system or relying on us to              maintain the databases schema.
        button:
          enable: ""
          label: "Request a Demo" 
          link: ""
      - title: CoCo Valuation
        subtitle: ''
        content: >-
          <ul><li>The price of the instrument with the various usual market conventions (clean or dirty, as a percentage of nominal).</li> <li>The price of the instrument assuming that it is called by the isuer at the next call date.</li>
          <li>The price of the instrument in the second regime, that is if a credit downgrade were to occur instantly.</li>
          <li>The Delta of the model (the first derivative of the price of the instrument with respect to the price of the stock of the underlying issuing  company). It is meaningful for CoCos which convert into equity upon trigger of the bail-in.</li><li>The yield to maturity in case of a T2 bond with finite maturity.</li><li>The yield to next call for a perpetual AT1 bond or a perpetual preferred share.</li><li>The optimal joint hedge ratios on the underlying and a CDS.</li></ul>
        beforeText: >-
          Once the model has been calibrated to the equity-to-credit universe, CoCo 33 proposes numerous functionalities to analyse the regulatory securities. CoCo 33 currently provides the following outputs for a given capital regulatory instrument:
        gallery:
        - image: "/images/spread.png"
          title: ""
        - image: "/images/model.png"
          title: ""
        button:
          enable: "true"
          label: "Request a Demo"
          link: "#requestdemo"
          popup: "true"
        afterText: >-
---

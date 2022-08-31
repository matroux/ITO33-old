---
title: Opscore
subtitle: The Convertible Bond  Pricing Solution
published: "2022-02-18T10:47:55Z"
description: |
  The complete front-office solution for the pricing, the hedging and the analysis of convertible securities.  It consists of four components: a data model of terms  and conditions, a pricing engine, analysis and simulation front-end and an excel screening tool.
image: "/images/solutions.jpg"
productImage: "/images/p1.jpg"
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


         <i class="fa fa-check"></i> ANALYSIS AND SIMULATION FRONT-END   

     
         <i class="fa fa-check"></i> EXCEL SCREENING TOOL  
        image: images/frontend.JPG
        subtitle: ''
        title: ' Opscore consists of four components:'
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
         Opscore is our complete front-office solution for the pricing, hedging and analysis of convertible securities. According to Sheen Kassouf and Edward Thorp              (co-authors of Beat the Market), a convertible security is “any security that may be exchanged for common stock”. In addition to warrants, Kassouf and Thorp's            classification includes convertible bonds, convertible preferred stocks, calls, stock rights and stock options. Opscore consists of four components:

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
      - title: EXCEL FRONT END
        subtitle: ''
        content: >-
             <ul><li>Using Microsoft Office Automation, the user can export all the terms and conditions of the convertible security from the Opscore data model to                  the Opscore Excel Analyzer. Several theoretical models can be defined and simulated on this worksheet. 3D surfaces of theoretical values and Greeks can                 be instantaneously plotted. More generally, every single output can be plotted as a function of every single input. This is achieved by the VBA                         routines of the Opscore Excel Analyzer, which, in turn, call the DLL of the pricing engine; moreover, the user can simulate terms and conditions                        different from the ones that are stored in the Opscore database, without affecting the stored data.</li>
               <li> Alternatively, users can build their own Excel spreadsheet, laying out the results of the pricing engine any way they please thanks to the Opscore                 XLL functions. The Opscore XLLs accept the identification number of the given security (its internal database code, ISIN, CUSIP, Bloomberg number or                   SEDOL) as an argument. This allows the XLLs to retrieve the corresponding terms and conditions from the Opscore database. The remaining arguments are                   the theoretical parameters (such as Brownian volatility and hazard rate). They are produced on the spreadsheet, either by calibration routines or by                    direct user input.</li></ul>
        beforeText: >-
          Since Excel is probably the most popular front end among traders and hedge fund managers, we made sure that all the results of Opscore are published to                  Excel. There are two ways the user may view these results:
        gallery:
        - image: "/images/frontendgrid.JPG"
          title: ""
        - image: "/images/frontendplot.JPG"
          title: ""
        button:
          enable: "true"
          label: "Request a Demo"
          link: "#requestdemo"
          popup: "true"
        afterText: >-
---

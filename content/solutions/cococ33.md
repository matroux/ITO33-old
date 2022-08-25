---
title: CoCo33
subtitle: Valuation and Risk Management Service 
description: |
 CoCo33 is a pricing and risk management framework for regulatory capital securities issued by banks following the Basel III capital adequacy requirements. It relies on a powerful equity-to-credit regime switching reduced form model with stochastic bail-in intensities and stochastic credit to analyse AT1 CoCo bonds, perpetual non-cumulative preferred shares and Tier 2 bonds issued by banks.
image: "/images/solutions.jpg"
productImage: "/images/coco3.png"
topInfo:
  enable: true
  type: breadcrumb
  bg: dark
  list:
  - text: Solutions
    link: "/solutions/"
  - text: CoCo33
    link: "#"
widgets:
  before:
    - enable: true
      type: solutions
      title: >-
        Valuation and risk management service     
        
        for regulatory capital securities
      subtitle: WE PROVIDE THE SOLUTION FOR ASSET MANAGEMENT
    - enable: true
      class: pt-5 c0l-12  bg-half mb-5
      type: banner
      layout: 
      title: RAVINTOLA JOKAISEEN MAKUUN
      bannerItem:
      - bg_image: images/backgrounds/about-us-bg.webp
        content: >-
         <i class="fa fa-check"></i> JOINT CALIBRATION    


         <i class="fa fa-check"></i> CONSISTENT PRICING OF ALL BANKING COCOS OF THE SAME ISSUER    


         <i class="fa fa-check"></i> COMPUTING OF RISK PARAMETERS INCLUDING BAIL-IN PROBABILITIES     
        image: images/Cocobanking.jpg
        subtitle: ''
        title: 'CoCo33 exhibits every output a risk manager can dream of'
        button:
          enable: "true"
          label: "Request a Demo"
          popup: "true"
          link: "#requestdemo"
    - enable: true
      type: accordian
      lists:
      - title: Overview
        subtitle: 'CoCo33'
        content: >-
          CoCo33 is a pricing and risk management framework for regulatory capital securities issued by banks following the Basel III  
          
          capital adequacy requirements. It can be extended to cover regulatory capital securities issued by insurance companies 
          according to the Solvency II regulations.    

          It relies on a powerful equity-to-credit regime switching reduced form model with stochastic bail-in intensities and stochastic credit to analyse AT1 CoCo bonds, perpetual non-cumulative preferred shares and Tier 2 bonds issued by banks. The regime switching model is jointly calibrated on the market quotes of all relevant securities related to the issuing bank such as credit default swaps, options and bonds, on top of the regulatory instruments themselves. Joint calibration allows for consistent pricing and leads to meaningful hedge ratios and risk parameters.    

          Once the model for the underlying issuing company is specified, either through calibration or manually, it can be used to evaluate the regulatory securities, to produce hedge ratios or risk parameters, or to analyse various risk scenarios. The product includes a database of terms and conditions and a technology to  serialize and store either the model parameters or the entire environment used in the calibration.    

          CoCo33 libraries are designed to integrate smoothly into existing risk management or front office systems. Excel add-ins offer an intuitive way to deploy the solution on a desk. A simple and intuitive Excel based utility is provided to test the various functionalities of the product.
        button:
          enable: ""
          label: "Request a Demo" 
          link: ""
      - title: The Regime Switching Model
        subtitle: ''
        content: >-
         A careful description of the credit process of the issuer is key to model the call feature present in AT1 CoCo bonds or non-cumulative preferred shares, and            therefore also the effective maturity of the instrument. 
         We use a regime switching model where each regime is a jump diffusion with its own volatility level. In each regime, a jump in the underlying share price may          be due to multiple factors. It could result from a regulatory or a contractual bail-in, or it could be due to default which sends the share price to zero.              Finally a switch between regimes is also associated with a jump in the underlying share price, thereby generating complex correlation patterns between                  volatility, share price, credit and bail-intensities.
         In practice two regimes are usually sufficient, although more complex structures with three regimes may be possible in some complex cases, in particular to            accommodate non monotonic CDS term structures. With two regimes, one of them can be labelled as the good state, while the other one is viewed as the bad state          for the issuing bank.
         The good state is typically the current situation, characterized by low volatility and a good credit rating, therefore with a low probability of default and            low intensty of bail-in. With some probability the bank may switch at any time to the bad state (think of it as a downgrade) characterized by a high risk of            default, a higher volatility level, and larger bail-in intensities. At the time of the switch or downgrade one would expect to see a significant negative jump          on the price of the underlying share price.
         The optimal decision to call the bond depends on the future regime, which renders both the timing of the call and the actual maturity of the bond stochastic.
         The parameters of this regime switching model are calibrated on all derivative quotes available for the issuing bank. In practice this often means a list of            American vanilla options and CDS quotes, a framework known as the Equity-to-Credit universe. 
         We consider up to three relevant CDS term structure: the ISDA 2003 subordinated and senior CDS curve and the ISDA 2014 subordinated curve. In absence of CDS            quotes, standard bond quotes of various maturities can be used to calibrate the credit component of the model.
         The regime switching model has been shown to capture efficiently a large number of derivative instruments in a consistent way, with the same model explaining          both the short term and the long term behaviour of the options and the credit default swaps.
         The conversion of a CoCo bond may be triggered mechanically by a particular CET1 level or it may be forced by the regulator at the point of non viability. We          consider a reduced form model where the bail-in of the CoCo bond is triggered by two Poisson processes whose intensities depends on the credit regime. One              Poisson process corresponds to the contracual bail-in which depends on the CET1 level while the other describes the regulatory bail-in. In a simple two regime          setting, the bail-in intensities in the current good credit state is low while they becomes significant in the bad regime.
         For the perpetual non-cumulative preferred shares issued by North American banks, we only consider the regulatory bail-in since these instruments do not have          a CoCo feature.
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
          Once the model has been calibrated to the equity-to-credit universe, CoCo33 proposes numerous functionalities to analyse the regulatory securities. CoCo33 currently provides the following outputs for a given capital regulatory instrument:
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

---
title: Volatility Management
subtitle: The Equity Derivatives    Pricing Expert
description: The variance swap is an equity derivative with payoff the realized variance of the underlying equity or index. Equity-to-Credit is the new form of volatility arbitrage. Credit risk (through the probability of the underlying equity jumping to zero) adds a component to option premium that cannot be financed by the usual rebalancing of the delta hedge issuing from the Black-Scholes-Merton model
image: "/images/solutions.jpg"
productImage: "/images/volatility.png"
topInfo:
  enable: true
  type: breadcrumb
  bg: dark
  list:
  - text: Solutions
    link: "/solutions/"
  - text: Volatility Management
    link: "#"
widgets:
  before:
    - enable: true
      type: solutions
      title: >-
           The Equity Derivatives Pricing Expert 
      subtitle: 
    - enable: true
      class: pt-5 c0l-12  bg-half mb-5
      type: banner
      layout: 
      title: RAVINTOLA JOKAISEEN MAKUUN
      bannerItem:
      - bg_image: images/backgrounds/about-us-bg.webp
        content: >-
         <i class="fa fa-check"></i> Vanilla options and volatility surfaces 
 
 
         <i class="fa fa-check"></i> Equity to Credit instruments, Bonds, Convertible Bonds, Contingent Conversion Bonds (CoCos), CDS, EDS, Credit Event Binary Options


         <i class="fa fa-check"></i> Barrier options 
         
         
         <i class="fa fa-check"></i> Digital options
         
         
         <i class="fa fa-check"></i> Forward starting options
         
         
         <i class="fa fa-check"></i> Variance swaps and option on variance
         
         
         <i class="fa fa-check"></i> VIX futures and VIX options
         
         
         <i class="fa fa-check"></i> Dividend swaps
          
         <i class="fa fa-check"></i> Gap options
    
        image: images/Cocobanking.jpg
        subtitle: ''
        title: ' Supported Instruments'
        button:
          enable: "true"
          label: "Request a Demo"
          popup: "true"
          link: "#requestdemo"
    - enable: true
      type: accordian
      lists:
      - title: VARIANCE SWAPS
        subtitle: 'Volatility Management'
        content: >-   
                 The variance swap is an equity derivative with payoff the realized variance of the underlying equity or index. The Black-Scholes-Merton tradition of                    We price the variance swaps under our generalized jump-diffusion model with stochastic volatility and stochastic jumps, also known as the “regime-                      switching model.”
                 We also price the log contract. This way, you can measure the difference due to the jumps.
                 It doesn't matter whether jumps (in the equity or the index) have been known to occur or not to occur in the past. (A jump to default couldn't have                    occurred in the past.) What matters is whether the market anticipates such jumps.
                 The empirical disconnect between the market price of the variance swap and the theoretical price of the log contract (a.k.a. the strip of vanillas),                    apparent even on the index, points in that direction.
                 We even calibrate the regime-switching model against the market prices of variance swaps of different starting dates and maturity dates, independently                  of the vanillas. Indeed, the variance swap is not redundant with the vanillas and its price carries additional information on the underlying process                    (as does the price of any path-dependent option, generally).
                 People should be suspicious, anyway, of any methodology that is incapable of valuing an instrument as natural and simple and homogeneous as the                        variance swap directly and says it requires a full strip of known vanilla options prices in order to do so!
                 On top of vanilla variance swaps, our all-numerical solving techniques enable us to price the following payoffs:
                 
          
                  All this is achieved in our general equity-to-credit framework, of which dividends and default risk are an integral part.

        button:
          enable: ""
          label: "Request a Demo" 
          link: ""
      - title: EQUITY TO CREDIT
        subtitle: ''
        content: >-
                Equity-to-Credit is the new form of volatility arbitrage. Credit risk (through the probability of the underlying equity jumping to zero) adds a                        component to option premium that cannot be financed by the usual rebalancing of the delta hedge issuing from the Black-Scholes-Merton model. Another                    hedging instrument has to be held and continuously traded in order to hedge the jump to default. Jointly inferring the Brownian volatility and the                      hazard rate from the market data of instruments sensitive both to volatility and credit risk (equity options, CDS) and computing the composite                          dynamic hedging strategy are the new rule of volatility arbitrage.
          
               THE EQUITY-TO-CREDIT PARADIGM 
               The equity-to-credit paradigm is born from the recognition that credit dependent instruments, starting with standard corporate bonds, have an                          embedded equity component which results from the high correlation between the credit standing of an issuer and its stock price. With corporate default                  of big companies looming large in the last few years, investors have been stunned by the collapse of the famed bond floor of convertible bonds. It is                  now well recognized that the credit component must be hedged with other standard instruments such as CDS or out of the money puts. More generally,                      equity and credit instruments should be priced and hedged in a unique consistent framework, which is the essence of the equity-to-credit paradigm.
               This creates both institutional and technical problems for market participants. Banks have traditionally traded their equity and credit portfolios in                  separate divisions which cannot cross-hedge their related exposures. Slowly and gradually, they are understanding that they need to merge the various                  desks which deal with the same issuer.
               Hedge funds have taken advantage of the institutional rigidity of banks; they have been the first to benefit from this new paradigm by investing in                    strategies which aim to arbitrage inconsistencies between the credit and the equity markets. But as more money is flowing into these strategies,                        obvious opportunities disappear and accurate modelling becomes essential. Traders have so far relied on software and models which are good at pricing                  one family of instruments but fail to deal consistently with the entire equity-to-credit spectrum. This is an issue for both pre-trade analysis and                    risk management.
                 

               SOLVING THE EQUITY-TO-CREDIT PROBLEM
               The Equity-to-Credit problem, as we understand it and handle it, is the problem of pricing and hedging of single name equity derivatives and credit                    derivatives when the issuer of the underlying equity is subject to default (or credit risk). Posing the problem means specifying the stochastic                        process followed by the underlying equity (typically, it is a jump-diffusion process where the diffusion, or Brownian component, admits of                              stochastic volatility and the jump component is a sum of Poisson jump processes with stochastic intensity and jump sizes, notable among which is the                    jump to default).
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

# 10 Cinematic Prompt Techniques for Video

> **What really works, what's hype, and how to use it.**

  -----------------------------------------------------------------------------------------
  \#       Technique             What It Does       Evidence & Notes        Verdict
  -------- --------------------- ------------------ ----------------------- ---------------
  **01**   **"Shot on ARRI       Signals the model  Camera names are style  **MIXED** ---
           Alexa"** *--- instant toward cinematic   signals, not technical  Leaning placebo
           cinema look*          color and          controls. Often bundled plus
                                 sharpness          with other tokens that  
                                 associated with    drive the actual look.  
                                 that camera.       Mixed results; weak     
                                                    standalone effect.      

  **02**   **Anamorphic lens,    Adds cinematic     Officially recommended  **MODERATE**
           horizontal lens       flares and         style token. Frequently --- Real
           flares** *---         widescreen         used across tools.      effect, not
           Hollywood spectacle*  character.         Adherence inconsistent; guaranteed
                                                    often dropped in        
                                                    complex prompts.        

  **03**   **Shallow depth of    Creates background "Shallow depth of       **STRONG** ---
           field, f/1.8** *---   blur and subject   field" works well.      Use descriptive
           professional bokeh*   separation.        Numeric f-stop is a     blur over
                                                    weaker lever. Models    numeric specs
                                                    approximate DOF rather  
                                                    than precisely          
                                                    controlling it.         

  **04**   **Volumetric light,   Adds visible light Well supported by       **STRONG** ---
           god rays through      rays and depth     official documentation  Descriptive
           atmospheric haze**    through            and testing. Describes  effects work
           *--- atmospheric      atmosphere.        a visual phenomenon     best
           depth*                                   models handle well.     

  **05**   **Skin pore detail,   Enhances skin      Effective for stills    **MODERATE**
           subsurface            realism with       and reference images.   --- Use in
           scattering** *---     natural texture    Over-specifying in      references,
           realistic faces*      and light          video prompts may       avoid overuse
                                 behavior.          introduce artifacts.    
                                                    Best used in a          
                                                    reference image.        

  **06**   **Slow push in,       Creates            One clear camera move   **STRONG** ---
           4-second clip** *---  intentional        performs best. Short    Recommended
           cinematic restraint*  movement and       clips (\~4 seconds)     
                                 improves prompt    adhere better. Official 
                                 adherence.         best practice across    
                                                    tools.                  

  **07**   **Practical lighting, Produces lighting  Highly recommended.     **STRONG** ---
           motivated source**    that feels natural Lighting is one of the  High-impact
           *--- believable       and story-driven.  biggest drivers of      technique
           lighting*                                perceived quality. Use  
                                                    real-world lighting     
                                                    sources and ratios.     

  **08**   **In the style of     Nudges the model   Refers to a style       **WEAK** ---
           \[specific            toward a known     cluster, not an exact   Supplement with
           cinematographer\]**   visual aesthetic.  lock. Better to         specifics
           *--- lock aesthetic*                     describe concrete       
                                                    techniques and          
                                                    palettes.               

  **09**   **24fps, natural      Aims for cinematic Frame rate is           **WEAK** ---
           motion blur** *---    motion cadence and determined by the model Frame-rate
           film-look motion*     blur.              or settings, not the    token has
                                                    prompt. "Motion blur"   little effect
                                                    has mild value. The     
                                                    24fps token is mostly   
                                                    redundant.              

  **10**   **Diegetic sound      Ensures audio      Documented for          **STRONG** ---
           only** *--- premium   comes from the     audio-capable models.   Excellent for
           audio realism*        scene itself.      Effective on systems    audio-capable
                                                    such as Sora and Veo    models
                                                    with native audio.      
                                                    Irrelevant for silent   
                                                    models.                 
  -----------------------------------------------------------------------------------------

## Key Takeaways

-   Be specific, not verbose.
-   Use one camera move and two or three modifiers.
-   Short clips adhere better.
-   Plain English often beats jargon.
-   Negative prompts can backfire.

## Prompt Formula That Works

**Camera Move** *(one clear move)*\
+ **Scene & Action** *(what's happening)*\
+ **Lighting & Look** *(motivated, cinematic)*\
+ **Duration** *(short and focused)*

------------------------------------------------------------------------

**Created by:** shaileesh, Founder of Beginnersblog.org

Newsletter: https://openailearning.org/subscribe

## Design Documentation

(following questions so that I can decide the **orientation** of the cards. Tried floating info on the canvas does not look good)

- hyper params only for the training window?
- parameters only for the layers window?
- shares train button and model status on all windows?
- maximum number of fields parameters can have? (if I select a layer with an activation I see upto 4 modifiable fields as key value pairs) 
- will remove grid if it looks bad or if it's too much trouble


- i'm assuming the shapes of the layers have significance?

(following one to one mapping from ENNUI to DnDML right?)

network --> models
progress --> training
visualization --> dataset
layers --> modules
templates --> prebuilt
... --> tuning
... --> architectures

differnece between models and modules?
are models just template


Unlike ENNUI no launch screen prompts. Presented to the dashboard directly. If going to have a learn option, have it on the topbar/toolbar?

*following assumes toolbar is necessary in design:* Ennui has higher categories: [network, progress, visualization] (and education) all decomposed further to options. Wasted space beside the options bar docked to the left side. If very few options can present them all directly in the top bar.

Easy front end implementation, use flat color scheme removed all gradients : simple global variables in SASS like [background, foreground, primary, secondary, hover, active] easier to maintain and change smaller code base and contrast is consistent across components so acessibility compliance with devtools easier

once specification becomes clear will implement with figma variants and then diretly html and css and js or use a webframework. all assets exported as SVGs simple color scheme and all cards max two appearence properties: radius and fill. will figure out responsive orientation for mobile devices. ENNUI works on mobile devices as well, so device agnostic and acessible

centered around customisability (not UI, ML stuff) no option paralysis

dark mode trusted palatte dracula-theme?


<!-- contending for side bar and open collapse to abstract out to topbar and entire side dock is selection subsectoins ennui to a degree but two side bars and icon crutch so reduce deadspace and floating palatte on the grid for stuff hover open and select stuff or side bar space hmm think about it and drag and drop to canvas prompt hover for purspose side side bar but mouse travel less so keyboard navigate simplest good and ? help on top smallest section approachable remoce and undesigns as much as you can

grid snapping make shapes a bit smaller

grid and mac clean up feature and auto that and no breaking exzess too? hmm dunno

not jsut minst loaded in but local directory as well to use it eh

figma
webflow
front end
blue palatte inviting light theme dark theme discord slack context separation
card abuse exessivly to only where neede

mouse travel side bar choice move to top and preview fast as you hover and very small set of opinionated shortcuts nice window in unofficial onvenion trigger to override mouse travel

dark mode trusted palatte dracula-theme instead of remixing would be nice but if not too hoherent in light to dark transition can change to a more muted theme good contrast fundamentals

create simple icons 

-->



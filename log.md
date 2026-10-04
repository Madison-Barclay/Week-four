I tried to follow the google collab notebook that was sent to me by email - trying to work out the errors I received last time I tried.
New error message: 
  - Block 2: ---------------------------------------------------------------------------
ImportError                               Traceback (most recent call last)
/tmp/ipykernel_6807/1251240677.py in <cell line: 0>()
      1 # Block 2
      2 from pathlib import Path
----> 3 from paddleocr import PaddleOCRVL
      4 
      5 # 1. Create a directory to store our structured outputs

11 frames
/usr/local/lib/python3.13/dist-packages/torch/__init__.py in <module>
    441     if USE_GLOBAL_DEPS:
    442         _load_global_deps()
--> 443     from torch._C import *  # noqa: F403
    444 
    445 

ImportError: /usr/local/lib/python3.13/dist-packages/torch/lib/libtorch_cuda.so: undefined symbol: ncclCommWindowDeregister

---------------------------------------------------------------------------
NOTE: If your import is failing due to a missing package, you can
manually install dependencies using either !pip or !apt.

To view examples of installing some common dependencies, click the
"Open Examples" button below.
---------------------------------------------------------------------------

Readings: 
  - 1. Billings estate PDF: need to review what a Quaker was 
  - 2. Getting it right and getting it wrong in digital archaeological ethics: emergence of digital archaeology has created new areas requiring ethical introspection
      - not yet adopted discipline wide standards related to archaeological ethics
      - Archaeology ungrounded in frameworks that specifically consider the ethical burdens of digital tools, methodology, and theory
      - Duty of care: archaeologists come from a place of privilege - must act responsibily towards the sites we excavate and the public
      - Ethics are not static - archaeologists have dealt with profound changes in the context of archaeology and profound changes in ethical concerns
      -  Current ethical issues: first issue how archaeological ethics could consider the digital tools that we use. Second issue is how archaeological ethics should consider the digital methodologies we employ. Third issue is how we should consider archaeological education and the digital (aka digital archaeological pedagogy)
      -  despite digital archaeology being a recent discipline to be published in the guidelines and codes of ethics of organizations this does not mean digital archaeology should not operate without ethical oversight
      -  Blackbox technologies in archaeology: digital photography, geographic information systems, and photogrammetry - even open source software packages like DGIS and R are used without full understanding of what underpins the package (so real, I feel this personally)
      -  For every tool under consideration: is this approach mediated digitally, fulfilling all of our needs for it, without adding undue ethical burden or breach? - if the answer to either of those questions is no, the use of the digital form should be weighed against the analog form
      -  Just because something can be accomplished faster, or easier, with a digital approach, doesn't mean that the ethics of that approach are equal!
      -  Ethical burden of projects involving human remains: both analog and digital methodologies have the same ethical burdens - on those involved with the project. added burdens of negotiating the potential differences in views towards digital permanence by indigenous populations and marginalized populations
      -  Problems in teaching digital archaeology: students not knowing the process of ethical questioning concerning their digital outputs and in the resources available to address those questions
      -  Digital tools and digital methodologies have yet to be synthesized fully into archaeological disucssion
      -  Digital archaeologits have a responsibility to consider the ethical burdens of our research, as well as the tools and methodologies that we utilize to accomplish our knowledge production goals

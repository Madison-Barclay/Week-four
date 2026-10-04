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
  - Billings estate PDF: need to review what a Quaker was 
  - getting it right and getting it wrong in digital archaeological ethics 

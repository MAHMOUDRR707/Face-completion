 # Face Completion
 
 I use of multi-output estimator to complete images. The goal is to predict the lower half of a face given its upper half.

The first column of images shows true faces. The next columns illustrate how extremely randomized trees, k nearest neighbors, linear regression and ridge regression complete the lower half of those faces.

Image completion, as a common image editing operation, aims to fill the missing or masked regions in images with plausibly synthesized contents. The generated
contents can either be as accurate as the original, or simply fit well within the context such that the completed image appears to be visually realistic. Most existing completion algorithms  rely on low-level cues to search for patches from known regions of the same image and synthesize the contents that locally appear similarly to the
matched patches. These approaches are all fundamentally constrained to copy existing patterns and structures from the known regions. The copy-and-paste strategy performs
particularly well for background completion (e.g., grass,sky, and mountain) by removing foreground objects and filling the unknown regions with similar pattens from backgrounds. However, the assumption of similar patterns can be found in the same image does not hold for filling missing parts of an object image (e.g., face). Many object parts contain unique patterns, which cannot be matched to other

![Result](https://user-images.githubusercontent.com/55753782/159600328-ed2f2752-1d2e-4cc2-8499-ae4bbc929da8.png)

# Underwater-Image-Enhancement

# Introduction
In the real-world underwater environment, underwater images generally suffer color distortion,low-contrast, detail blurring, color-cast due to the behaviour of light in the water medium.This is due to the properties called light scattering and absorption of wavelength which ad-versely affect the visibility of the underwater images. Underwater images 
play a vital rolein the fields of marine archaeology, military surveillance, Oceanography, etc. Existing under-water image enhancement techniques do not handle all the degradation factors. To handleall the degradation factors, we propose a single image approach for underwater image en-hancement.  Unlike the existing works that require the parameters of underwater imagingmodel estimation, our approach directly enhances the underwater image without the priorknowledge of light properties and imaging models.  Our approach includes dehazing, colorcorrection, multi-scale fusion and exposure fusion for contrast enhancement. The dehazingand color correction methods remove the haze and the color cast from the image.  Thesetwo images are used as input to the multiscale fusion which consists of weight maps such assaliency, Laplacian and saturation. In addition, to enhance the contrast in the scene we usedan exposure fusion framework-based algorithm, which estimates weight matrix and accuratelyenhances the contrast of the output image. Our detailed experiments on real time underwa-ter datasets demonstrate that the proposed method achieves better visual quality, improvedglobal contrast, and accurate color restoration and comparable performance than the otherstate of the art methods in terms of qualitative and quantitative assessments.

The project aims at enhancing real-time underwater images using python.
  
# Here is a list of libraries you need to install to execute the code:

1) Python =3.6 or above
2) cv2
3) numpy 
4) scipy
5) matplotlib
6) scikit-image
7) natsort
8) math
9) pandas
10) globe
11) os
12) sewar


# Easy Usage:

1. After installing python 3.6 or above, 
      complete the running environment configuration.
2. Install all of the above libraries through anaconda command prompt. 
3. Run the files individually to check whether the libraries are installed or not.
4. Run python main.py.
5. Find the enhanced image in "output_image" folder. 


# Reference papers:
Underwater Image Color Restoration

1) DCP: Single Image Haze Removal Using Dark Channel Prior (2011)
2) GBdehazingRCorrection: Single underwater image restoration by blue-green channels dehazing and red channel correction (2016)
3) IBLA: Underwater Image Restoration Based on Image Blurriness and Light Absorption (2017)
4) LowComplexityDCP: Low Complexity Underwater Image Enhancement Based on Dark Channel Prior (2011)
5) MIP: Initial results in underwater single image dehazing (2010)
6) NewOpticalModel: Single underwater image enhancement with a new optical model (2013)
7) RoWS: Removal of water scattering (2010)
8) UDCP: Transmission Estimation in Underwater Single Images (2013)
9) ULAP: A Rapid Scene Depth Estimation Model Based on Underwater Light Attenuation Prior for Underwater Image Restoration (2018)

Underwater Image Enhancement

10) CLAHE: Contrast limited adaptive histogram equalization (1994)
11) Fusion-Matlab: Enhancing underwater images and videos by fusion (2012)
12) GC: Gamma Correction
13) HE: Image enhancement by histogram transformation (2011)
14) ICM: Underwater Image Enhancement Using an Integrated Colour Model (2007)
15) RGHS: Shallow-Water Image Enhancement Using Relative Global Histogram Stretching Based on Adaptive Parameter Acquisition (2018)
16) RayleighDistribution: Underwater image quality enhancement through composition of dual-intensity images and Rayleigh-stretching (2014)
17) UCM: Enhancing the low quality images using Unsupervised Colour Correction Method (2010)

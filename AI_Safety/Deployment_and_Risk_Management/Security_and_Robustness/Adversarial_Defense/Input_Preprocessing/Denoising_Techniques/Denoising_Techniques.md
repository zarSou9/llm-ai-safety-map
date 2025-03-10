### Mini Description

Approaches that treat adversarial perturbations as a form of noise and apply various denoising algorithms to recover clean inputs, including traditional signal processing methods and learned denoisers.

### Description

Denoising techniques in adversarial defense focus on treating adversarial perturbations as a form of signal corruption that can be removed through specialized filtering and reconstruction methods. These approaches leverage both classical signal processing theory and modern deep learning techniques to identify and eliminate potential adversarial components while preserving the underlying semantic content of inputs. The fundamental challenge lies in distinguishing between legitimate features and malicious perturbations, especially when adversarial modifications are designed to be imperceptible.

The field encompasses both model-free methods, which rely on statistical properties of natural data and noise patterns, and learned approaches that utilize neural networks trained specifically for denoising tasks. Traditional techniques include methods like median filtering, bilateral filtering, and wavelet thresholding, while modern approaches often employ autoencoders, energy-based models, or specialized architectures designed to learn the manifold of clean data. A key consideration is the computational efficiency of these methods, as they must process inputs in real-time for many applications.

Current research challenges include developing denoising methods that remain effective against adaptive attackers who can optimize around known preprocessing steps, creating approaches that scale efficiently to high-dimensional inputs, and designing techniques that can handle various types of adversarial perturbations without compromising performance on clean inputs. There is particular interest in methods that can provide theoretical guarantees about their denoising properties while maintaining practical applicability.

### Order

1. Statistical_Filtering
2. Transform_Domain_Methods
3. Learning-Based_Denoisers
4. Optimization-Based_Recovery
5. Ensemble_Denoising

# Herbarium: A Simulation of a Medieval Herbary

This project simulates a system of traditional medicine, inspired by the principles of Humorism and the Doctrine of Signatures, emulating a medieval herbary.

## Description

**Historical Context**

Medieval herbaries were comprehensive guides to plants and their medicinal properties. These texts often included detailed descriptions of plants, their astrological associations, and their applications in treating various ailments. The knowledge within these herbaries was rooted in ancient medical systems like Humorism, which viewed the body as a balance of four humors—choler, melancholy, sanguine, and phlegmatic—and the Doctrine of Signatures, which posited that a plant's appearance could indicate its medicinal uses.

**Simulation Approach**

This simulation captures the essence of a medieval herbary by representing plants, diseases, and body types (based on the four humors) using matrices. These matrices reflect the elemental qualities of each entity—fire, earth, air, and water—as well as their associated humoral qualities. 

The simulation leverages the following key principles:

*   **Humorism:** Body types are categorized based on the dominant humor, which influences their elemental properties.
*   **Doctrine of Signatures:** While not explicitly simulated, the underlying concept that "like cures like" is reflected in the relationship between plant and disease properties.
*   **Elemental Qualities:** Plants and diseases are assigned elemental qualities, reflecting their traditional properties (e.g., a plant associated with fire might be warming and stimulating).
*   **PCA (Principal Component Analysis):** PCA is used to reveal underlying relationships between plants and diseases based on their elemental and humoral properties. This provides a multi-dimensional understanding of the interactions within the system.

## Usage

**Interactive Exploration**

1.  **Select a body type (humor):** Choose from the four humors (choler, melancholy, sanguine, phlegmatic) to simulate a specific body type.
2.  **Select a disease:** Choose from a list of diseases to explore potential treatment options.
3.  **Select a season:** Consider the seasonal influences on the body and how they might impact treatment.
4.  **Adjust effects:** Use sliders to control the influence of the selected plant and disease on the body.
5.  **Visualization:** Radar charts provide a visual representation of the properties of the body, disease, and recommended plants, allowing for comparison and analysis.
6.  **Optimization:** Click "Find Best Plant" to identify the most suitable plant for the selected condition based on the simulation's calculations.

**Random Scenarios and Exploration**

*   Click "Randomize All" to generate a random selection of body type, disease, and season, allowing for exploration of diverse cases and potential remedies.

## Requirements

*   Python 3.x
*   Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, IPython

## Installation

1.  Clone this repository.
2.  Install the necessary libraries using `pip install -r requirements.txt`.

## Example

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exoplanet ML</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
            background-color: #f9f9f9;
            color: #333;
        }
        h1, h2, h3 {
            color: #2c3e50;
        }
        a {
            color: #2980b9;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        ul {
            list-style-type: disc;
            margin-left: 20px;
        }
        pre {
            background-color: #eef;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
        code {
            background-color: #eef;
            padding: 2px 4px;
            border-radius: 4px;
        }
        .toc ul {
            list-style-type: none;
            padding-left: 0;
        }
        .toc li {
            margin-bottom: 5px;
        }
        .section {
            margin-bottom: 40px;
        }
    </style>
</head>
<body>
    <h1>Exoplanet ML</h1>
    <p>Exoplanet ML is a machine learning project dedicated to the detection of exoplanets using transit survey-based light curves. This project leverages advanced machine learning algorithms and feature engineering techniques to improve the accuracy and efficiency of exoplanet discovery.</p>

 <div class="toc section">
        <h2>Table of Contents</h2>
        <ul>
            <li><a href="#features">Features</a></li>
            <li><a href="#machine-learning-algorithms">Machine Learning Algorithms</a></li>
            <li><a href="#important-notebooks">Important Notebooks</a></li>
            <li><a href="#important-links">Important Links</a></li>
            <li><a href="#dimensionality-reduction">Dimensionality Reduction</a></li>
            <li><a href="#tsfresh-feature-selection">TsFresh Feature Selection</a></li>
            <li><a href="#installation">Installation</a></li>
            <li><a href="#usage">Usage</a></li>
            <li><a href="#contributing">Contributing</a></li>
            <li><a href="#license">License</a></li>
        </ul>
    </div>

<div class="section" id="features">
        <h2>Features</h2>
        <ul>
            <li>Detection of exoplanets using transit-based light curves</li>
            <li>Implementation of various machine learning classifiers</li>
            <li>Advanced feature engineering with time-series data</li>
            <li>Dimensionality reduction for improved model performance</li>
            <li>Comprehensive Jupyter notebooks for exploration and analysis</li>
        </ul>
    </div>

<div class="section" id="machine-learning-algorithms">
        <h2>Machine Learning Algorithms</h2>
        <ul>
            <li>Random Forest Classifier</li>
            <li>Naive Bayes</li>
            <li>LightGBM</li>
            <li>XGBoost</li>
            <li>AdaBoost</li>
            <li>Histogram Gradient Boosting</li>
            <li>Multi-Layer Perceptron</li>
            <li>Neural Network</li>
        </ul>
    </div>

<div class="section" id="important-notebooks">
        <h2>Important Notebooks</h2>
        <ul>
            <li><a href="https://spacetelescope.github.io/notebooks/notebooks/MAST/Kepler/Kepler_Lightcurve/kepler_lightcurve.html" target="_blank" rel="noopener noreferrer">Kepler Lightcurve Analysis</a></li>
            <!-- Add more notebooks here as needed -->
        </ul>
    </div>

<div class="section" id="important-links">
        <h2>Important Links</h2>
        <ul>
            <li><a href="https://www.rasgoml.com/feature-engineering-tutorials/how-to-create-time-series-features-with-tsfresh" target="_blank" rel="noopener noreferrer">Feature Engineering with TsFresh</a></li>
            <li><a href="https://exoplanetarchive.ipac.caltech.edu/docs/acknowledge.html" target="_blank" rel="noopener noreferrer">Exoplanet Archive Acknowledgement</a></li>
            <li><a href="https://exoplanetarchive.ipac.caltech.edu/docs/doi.html" target="_blank" rel="noopener noreferrer">Exoplanet Archive DOI</a></li>
            <li><a href="https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=kep_conf_names" target="_blank" rel="noopener noreferrer">Exoplanet Archive Table</a></li>
            <li><a href="https://exoplanetarchive.ipac.caltech.edu/docs/table-redirect.html" target="_blank" rel="noopener noreferrer">Exoplanet Archive Table Redirect</a></li>
        </ul>
    </div>

<div class="section" id="dimensionality-reduction">
        <h2>Dimensionality Reduction</h2>
        <ul>
            <li><a href="https://www.kaggle.com/code/samuelcortinhas/intro-to-pca-t-sne-umap" target="_blank" rel="noopener noreferrer">Introduction to PCA, t-SNE, and UMAP</a></li>
            <li><a href="https://plotly.com/python/t-sne-and-umap-projections/" target="_blank" rel="noopener noreferrer">Plotly: t-SNE and UMAP Projections</a></li>
            <li><a href="https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.KernelPCA.html" target="_blank" rel="noopener noreferrer">KernelPCA in Scikit-Learn</a></li>
            <li><a href="https://pair-code.github.io/understanding-umap/" target="_blank" rel="noopener noreferrer">Understanding UMAP</a></li>
            <li><a href="https://umap-learn.readthedocs.io/en/latest/basic_usage.html" target="_blank" rel="noopener noreferrer">UMAP Basic Usage</a></li>
        </ul>
    </div>

<div class="section" id="tsfresh-feature-selection">
        <h2>TsFresh Feature Selection</h2>
        <ul>
            <li><a href="https://tsfresh.readthedocs.io/en/latest/api/tsfresh.feature_selection.html" target="_blank" rel="noopener noreferrer">TsFresh Feature Selection Documentation</a></li>
            <li><a href="https://blog.mindmetawithminesh.com/tsfresh-feature-extraction-by-distributed-and-parallel-means-for-industrial-big-data-applications-d84e97047024" target="_blank" rel="noopener noreferrer">TsFresh Feature Extraction for Industrial Big Data Applications</a></li>
        </ul>
    </div>

<div class="section" id="installation">
        <h2>Installation</h2>
        <p>Follow these steps to set up the Exoplanet ML project locally:</p>
        <pre><code>git clone https://github.com/yourusername/exoplanet-ml.git
cd exoplanet-ml
pip install -r requirements.txt
</code></pre>
        <p>Ensure you have Python 3.7 or higher installed. It's recommended to use a virtual environment:</p>
        <pre><code>python -m venv venv
source venv/bin/activate  <!-- On Windows use `venv\Scripts\activate` -->
pip install -r requirements.txt
</code></pre>
    </div>

<div class="section" id="usage">
        <h2>Usage</h2>
        <p>After installation, you can start by exploring the Jupyter notebooks provided. To launch Jupyter Notebook, run:</p>
        <pre><code>jupyter notebook
</code></pre>
        <p>Navigate to the desired notebook (e.g., <code>Kepler_Lightcurve.ipynb</code>) and execute the cells to begin analyzing exoplanet light curves.</p>
        <p>For command-line usage or integration into your own scripts, refer to the <code>src/</code> directory where the main modules and scripts are located.</p>
    </div>

<div class="section" id="contributing">
        <h2>Contributing</h2>
        <p>Contributions are welcome! To contribute to Exoplanet ML, please follow these guidelines:</p>
        <ol>
            <li>Fork the repository on GitHub.</li>
            <li>Clone your fork to your local machine:</li>
            <pre><code>git clone https://github.com/yourusername/exoplanet-ml.git
cd exoplanet-ml
</code></pre>
            <li>Create a new branch for your feature or bugfix:</li>
            <pre><code>git checkout -b feature/your-feature-name
</code></pre>
            <li>Make your changes and commit them with clear messages:</li>
            <pre><code>git commit -m "Add feature XYZ"
</code></pre>
            <li>Push your changes to your fork:</li>
            <pre><code>git push origin feature/your-feature-name
</code></pre>
            <li>Open a pull request on the main repository describing your changes.</li>
        </ol>
        <p>Please ensure your code follows the project's coding standards and includes appropriate tests.</p>
    </div>

<div class="section" id="license">
        <h2>License</h2>
        <p>This project is licensed under the <a href="LICENSE" target="_blank" rel="noopener noreferrer">MIT License</a>. You are free to use, modify, and distribute this project as per the license terms.</p>
    </div>
</body>
</html>

# Erick Hecht López

**Data Science | Applied AI | Mining & Geospatial Analytics | Healthcare Analytics**

Medical Technologist specializing in MRI, with a bachelor's-level degree in Applied Engineering (Informatics) and currently a Master's candidate in Data Science at Universidad de Santiago de Chile (USACH).

I develop applied analytics projects that combine domain knowledge, statistical reasoning, machine learning, geospatial analysis and reproducible software practices.

My current public portfolio focuses on mining and geospatial analytics, while additional work in healthcare and business analytics is being reviewed and curated for publication.

## Featured Project

### Mining & Geospatial Analytics

[Explore the Mining Geospatial Analytics portfolio](https://github.com/EHDataAI/mining-geospatial-analytics)

A progressive portfolio applying geospatial data science, spatial machine learning and GeoAI methods to mineral exploration and mining problems.

Current public work includes:

- **LAB 01A - Coordinate Foundations**
- **LAB 01B - Cross-Zone CRS Analysis**
- **LAB 02 - Spatial Exploratory Data Analysis**
- **LAB 03 - Spatial Cross-Validation**
- **31 automated tests**
- reproducible Conda environments
- automated validation with GitHub Actions
- pre-commit quality controls and secret scanning
- signed Git commits and pull-request based validation

The portfolio currently demonstrates how coordinate reference systems, sampling density, spatial aggregation, validation geometry and analytical choices can materially affect scientific interpretation.

One example compares geodesic and projected distance calculations across UTM zones, showing how technically executable spatial operations can still produce scientifically invalid results when coordinate systems are misused.

LAB 02 extends this approach by examining the distinction between apparent spatial hotspots and uneven sampling intensity through controlled synthetic experiments and sensitivity analysis.

LAB 03 extends the portfolio into spatial model validation. It compares conventional Random K-Fold with Spatial Block Cross-Validation and demonstrates how spatial proximity between training and validation observations can produce optimistic estimates of predictive performance.

For the primary 5 km spatial-block scenario, Random K-Fold produced a pooled RMSE of **3.9676**, compared with **4.2610** under Spatial Block Cross-Validation, corresponding to **6.89% relative RMSE optimism** in this controlled synthetic experiment.

The result is treated as experiment-specific rather than as a universal correction factor. The laboratory also evaluates 10 km blocks as a sensitivity analysis and 20 km blocks as a stress test, illustrating the trade-off between stronger spatial separation and reduced validation support.

### Roadmap

**Completed**

Coordinate Foundations -> Cross-Zone CRS Analysis -> Spatial EDA -> Spatial Cross-Validation

**Next**

Geochemical CoDA -> Mineral Prospectivity Mapping -> Explainability -> Uncertainty -> Remote Sensing -> Deep Learning -> Graph & Multimodal GeoAI

## Technical Stack

**Data Science**

Python | R | pandas | Polars | NumPy | SciPy | scikit-learn | Jupyter

**Geospatial Analytics**

GeoPandas | Shapely | PyProj | Rasterio

**Engineering & Quality**

Git | GitHub | Conda | pytest | pre-commit | GitHub Actions | Gitleaks

## Areas of Applied Work

### Mining & Geospatial Analytics

Spatial analysis, geospatial data engineering, spatial machine learning and reproducible analytical workflows for mineral exploration and mining.

### Healthcare Analytics

Applied analytics for medical imaging, operational performance and healthcare information systems, informed by professional experience in MRI and medical imaging.

### Data Science & Applied AI

Statistical modelling, machine learning, reproducible experimentation and analytical pipelines across applied domains.

## Working Principles

I focus on analytical work that is reproducible, auditable and scientifically defensible.

This includes:

- validating assumptions before increasing model complexity;
- preventing data leakage, including spatial leakage;
- separating exploratory analysis from reusable production-oriented code;
- comparing advanced methods against interpretable baselines;
- using automated testing where appropriate;
- maintaining traceable version control and signed commits;
- validating changes through pull requests and continuous integration;
- communicating limitations, uncertainty and methodological assumptions explicitly.

## Current Development

The public portfolio is being expanded progressively.

LAB 04 will extend the current geospatial validation foundation into geochemical compositional data analysis, while maintaining the same emphasis on reproducibility, explicit assumptions, validation design and scientific interpretation.

Additional projects in healthcare analytics, machine learning and applied data science are also being reviewed and curated before publication.

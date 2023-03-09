# Quick start
You can install and run Mage using Docker (recommended), pip, or conda.

Install using Docker
Create a new project and launch tool (change demo_project to any other name if you want):
```bash
docker run -it -p 6789:6789 -v $(pwd):/home/src mageai/mageai \
  /app/run_app.sh mage start demo_project
```

Want to use Spark or other integrations? Read more about integrations.

Open http://localhost:6789 in your browser and build a pipeline.

Using pip or conda
Install Mage
```
pip install mage-ai
```
or
```
conda install -c conda-forge mage-ai
```
For additional packages (e.g. spark, postgres, etc), please see Installing extra packages.

If you run into errors, please see Install errors.

Create new project and launch tool (change demo_project to any other name if you want):

mage start demo_project
Open http://localhost:6789 in your browser and build a pipeline.
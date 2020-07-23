# Scaling Jupyter Notebooks with Kubeflow Pipelines

The `KF_MNIST.ipynb` notebook is designed to show [Kubeflow Pipelines](https://www.kubeflow.org/docs/pipelines/overview/pipelines-overview/) functionality.

Instructions on how to install Kubeflow on a Kubernetes cluster can be found [here](https://www.linode.com/docs/kubernetes/how-to-deploy-kubeflow-on-linode-kubernetes-engine/). This resource also includes instructions on creating Jupyter Notebooks. 

Once Kubeflow is installed, [create a Notebook](https://www.kubeflow.org/docs/notebooks/setup/). Once your notebook is ready, you should be able to clone the current repository by opening it and navigating to `New` -> `Terminal`. 

In the terminal, run the following command:

`git clone https://github.com/learnk8s/kubeflow-pipelines-demo.git`

Once cloned, if you switch back to the notebook, you will see `kubeflow-pipelines-demo` folder which will include the `KF_MNIST.ipynb` notebook.

At the end of the execution of the notebook, in Kubeflow dashboard, navigate to `Pipelines` -> `Experiments` and you should see the experiment that notebook just created in the pipelines.

must-gather
===========

`must-gather` is a tool based on [`openshift-must-gather`](https://www.github.com/openshift/must-gather) to collect data from `kubernetes` to review and support it's overall state and health.

## Collection Scripts
Data collection scripts are kept in `./collection-scripts`.  The content of that folder is placed in `/usr/bin` in the image. Also the required `oc` binary required in the `must-gather` can be found on [Client tools for OKD](https://github.com/okd-project/okd/releases).

## How to run
It's recommend to run the `must-gather` using `oc adm must-gather --image=quay.io/<repo>/kube-must-gather:latest`. To obtain the `oc` binary, refer to [Client tools for OKD](https://github.com/okd-project/okd/releases).

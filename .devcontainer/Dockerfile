FROM python:3.12
RUN apt-get update -y && \
    apt-get upgrade -y

RUN pip3 install --upgrade pip && \
    pip3 install -U poetry

# [Optional] Uncomment this section to install additional OS packages.
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends <your-package-list-here>

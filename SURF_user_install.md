SURF has installed the software on debian12 the standard kernel 6.1.0 (linux-image-6.1.0) is not compiled wuth the DMABUF settings. We haev installed a debian kernel from backports 6.12.43+deb12 this has the needed settings for the metis kernel driver

This is the installation instruction for SURF ETP users:

    git clone https://github.com/basvandervlies/voyager-sdk
    git checkout surf_1.5

Now install the runtime environment in your home directory:

    `./install.sh --runtime

When finished:

    source venv/bin/activate
    axdevice

DepthAI Hardware Documentation
==============================

Each device's documentation includes an overview, getting started guide, images and project files (such as datasheets), Altium design files, 3D models, and
mechanical models.

Device name guide
*****************

.. image:: /_static/images/device-comparison/device-naming.png
     :target: pages/guides/device-comparison.html

More information can be found at :ref:`Device comparison` guide.

USB Designs
***********

These are our most popular devices. Brought to market by a successful `KickStarter <https://www.kickstarter.com/projects/opencv/opencv-ai-kit>`__ campaign,
OAK-D and OAK-1 products have been solving real-world problems since 2019. **USB connection** is great for development - it's easy to use and allows up to
10Gbps throughput.


.. list-table::
   :header-rows: 1

   * - OAK-D Lite
     - OAK-D S2
     - OAK-D Pro
   * - .. image:: /_static/images/thumbnails/DM9095.png
          :target: pages/DM9095.html
     - .. image:: /_static/images/thumbnails/DM9098s2.png
          :target: pages/DM9098s2.html
     - .. image:: /_static/images/thumbnails/DM9098pro.png
          :target: pages/DM9098pro.html
   * - :ref:`Learn more <dm9095>`
     - :ref:`Learn more <dm9098s2>`
     - :ref:`Learn more <dm9098pro>`

.. list-table:: Variable Stereo Baseline distance
   :header-rows: 1

   * - OAK-D SR (Short Range)
     - OAK-D
     - OAK-D LR (Long Range)
   * - .. image:: /_static/images/thumbnails/oak-d-sr_th.png
          :target: pages/OAK-D-SR.html
     - .. image:: /_static/images/thumbnails/BW1098OAK.png
          :target: pages/BW1098OAK.html
     - .. image:: /_static/images/thumbnails/oak-d-lr.png
          :target: pages/OAK-D-LR.html
   * - :ref:`Learn more <OAK-D SR>`
     - :ref:`Learn more <bw1098oak>`
     - :ref:`Learn more <OAK-D LR>`


.. list-table:: Wide Field of View USB devices
   :header-rows: 1

   * - OAK-1 Lite W
     - OAK-1 W
     - OAK-D W
     - OAK-D Pro W
   * - .. image:: /_static/images/thumbnails/oak-1-lite-w.png
          :target: pages/NG9096litew.html
     - .. image:: /_static/images/thumbnails/oak-1-w.png
          :target: pages/NG9096w.html
     - .. image:: /_static/images/thumbnails/oak-d-w_th.png
          :target: pages/DM9098w.html
     - .. image:: /_static/images/thumbnails/OAK-D-Pro-W_th.png
          :target: pages/DM9098prow.html
   * - :ref:`Learn more <ng9096litew>`
     - :ref:`Learn more <ng9096w>`
     - :ref:`Learn more <dm9098w>`
     - :ref:`Learn more <dm9098prow>`


.. list-table:: OAK-1 variations with different camera sensors
   :header-rows: 1

   * - OAK-1 Lite
     - OAK-1
     - OAK-1 MAX
   * - .. image:: /_static/images/thumbnails/oak-1-lite.png
          :target: pages/NG9096.html
     - .. image:: /_static/images/thumbnails/oak-1.png
          :target: pages/BW1093.html
     - .. image:: /_static/images/thumbnails/oak-1-max.png
          :target: pages/NG9096max.html
   * - :ref:`Learn more <ng9096>`
     - :ref:`Learn more <bw1093>`
     - :ref:`Learn more <ng9096max>`

PoE Designs
***********

PoE devices are similar to USB devices, but instead of USB they have **PoE connectivity** and also feature **on-board flash**, so you can run pipelines
in `standalone mode <https://docs.luxonis.com/projects/api/en/latest/tutorials/standalone_mode/>`__.

.. list-table::
   :header-rows: 1

   * - OAK-D PoE
     - OAK-D S2 PoE
     - OAK-D Pro PoE
   * - .. image:: /_static/images/thumbnails/oak-d-poe_th.png
          :target: pages/SJ2088POE.html
     - .. image:: /_static/images/thumbnails/oak-d-s2-poe.png
          :target: pages/NG9097s2.html
     - .. image:: /_static/images/thumbnails/oak-d-pro-poe.png
          :target: pages/NG9097pro.html
   * - :ref:`Learn more <sj2088poe>`
     - :ref:`Learn more <ng9097s2>`
     - :ref:`Learn more <ng9097pro>`

.. list-table::
   :header-rows: 1

   * - OAK-1 PoE
     - OAK-D W PoE
     - OAK-D Pro W PoE
   * - .. image:: /_static/images/thumbnails/OAK-1-PoE_th.png
          :target: pages/SJ2096POE.html
     - .. image:: /_static/images/thumbnails/oak-d-w-poe.png
          :target: pages/NG9097w.html
     - .. image:: /_static/images/thumbnails/oak-d-pro-w-poe.png
          :target: pages/NG9097prow.html
   * - :ref:`Learn more <sj2096>`
     - :ref:`Learn more <ng9097w>`
     - :ref:`Learn more <ng9097prow>`

Modular Camera Designs
**********************

The **OAK FFC line** is great for prototyping flexibility. Since **cameras are modular**, you can place them at **various stereo baselines**. This flexibility comes with a
trade: you have to figure out how/where you will mount them, and then once mounted, perform a `stereo calibration <https://docs.luxonis.com/en/latest/pages/calibration/>`__.
This is not a TON of work, so keep in mind that these aren't "plug and play" like other options. Instead, they are more for applications that require custom mounting,
custom baseline, or custom orientation of the cameras.

.. list-table::
   :header-rows: 1

   * - OAK-FFC 3P
     - OAK-FFC 4P
     - OAK-FFC 6P
     - FFC Camera modules
   * - .. image:: /_static/images/thumbnails/OAK-FFC-3P_th.png
          :target: pages/DM1090.html
     - .. image:: /_static/images/thumbnails/OAK-FFC-4P_th.png
          :target: pages/DD2090.html
     - .. image:: /_static/images/thumbnails/FFC-6P.png
          :target: pages/DM3390.html
     - .. image:: /_static/images/thumbnails/OAK-FFC_modules_th.png
          :target: pages/ffc-cameras.html
   * - :ref:`Learn more <dm1090ffc>`
     - :ref:`Learn more <dd2090ffc>`
     - :ref:`Learn more <dm3390>`
     - :ref:`Learn more <arducam>`

.. list-table::
   :header-rows: 1

   * - OAK-FFC IMX378
     - OAK-FFC OV9282
     - OAK-FFC IMX582
     - OAK-FFC ToF VGA
   * - .. image:: /_static/images/thumbnails/BG0249.png
          :target: pages/BG0249.html
     - .. image:: /_static/images/thumbnails/BG0250TG.png
          :target: pages/BG0250TG.html
     - .. image:: /_static/images/thumbnails/oak-ffc-48mp.png
          :target: pages/DM0260imx582.html
     - .. image:: /_static/images/thumbnails/DM0256.png
          :target: pages/DM0256.html
   * - :ref:`Learn more <bg0249>`
     - :ref:`Learn more <bg0250tg>`
     - :ref:`Learn more <DM0260imx582>`
     - :ref:`Learn more <dm0256>`

.. _som_designs:

System on Module (SoM) Designs
******************************

A SoM is perfect :ref:`for integrating <Integrating DepthAI into products>` the power of DepthAI into your own products, or to customize one of our
open-source hardware designs as you see fit.

.. list-table::
   :header-rows: 1

   * - OAK-SoM
     - OAK-SoM Pro
     - OAK-SoM MAX
   * - .. image:: /_static/images/thumbnails/BW1099.png
          :target: pages/BW1099.html
     - .. image:: /_static/images/thumbnails/oak-som-pro.png
          :target: pages/BW2099.html
     - .. image:: /_static/images/thumbnails/dm3399.png
          :target: pages/DM3399.html
   * - :ref:`Learn more <bw1099>`
     - :ref:`Learn more <bw2099>`
     - :ref:`Learn more <dm3399>`

Other Designs
*************

.. list-table::
   :header-rows: 1

   * - OAK-D CM4
     - OAK-D CM4 PoE
     - OAK Y-Adapter
   * - .. image:: /_static/images/thumbnails/DM1097.png
          :target: pages/DM1097.html
     - .. image:: /_static/images/thumbnails/OAK-D-CM4-PoE_th.png
          :target: pages/DM2097.html
     - .. image:: /_static/images/thumbnails/Y_Adapter_th.png
          :target: pages/DM6010.html
   * - :ref:`Learn more <dm1097>`
     - :ref:`Learn more <dm2097>`
     - :ref:`Learn more <Y-adapter>`


Some **older models** can be :ref:`found here <Other models>`.

.. include::  /pages/includes/footer-long.rst


.. toctree::
   :maxdepth: 0
   :hidden:
   :caption: Guides

   pages/guides/device-comparison.rst
   pages/guides/realsense_comparison.rst
   pages/guides/getting-started-with-poe.rst
   pages/guides/powering_poe_devices.rst
   pages/guides/calibration.rst
   pages/guides/integrating_depthai_into_products.rst
   pages/guides/sync_frames.rst
   pages/guides/raspberrypi.rst
   pages/guides/af_ff.rst

.. toctree::
   :maxdepth: 0
   :hidden:
   :caption: Articles

   pages/articles/waterproof.rst
   pages/articles/operative_temperature_range.rst
   pages/articles/device_availability_and_eol.rst
   pages/articles/supported_sensors.rst

.. toctree::
     :caption: Series
     :hidden:

     pages/articles/oak-s2.rst
     pages/articles/oak-s3.rst

.. toctree::
     :caption: Robotics Vision Core
     :hidden:

     pages/rvc/rvc2.rst
     pages/rvc/rvc3.rst

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: USB Designs

   pages/DM9098pro.rst
   pages/DM9098prow.rst
   pages/DM9098s2.rst
   pages/DM9098w.rst
   pages/OAK-D-LR.rst
   pages/OAK-D-SR.rst
   pages/BW1098OAK.rst
   pages/DM9095.rst
   pages/BW1093.rst
   pages/NG9096w.rst
   pages/NG9096max.rst
   pages/NG9096.rst
   pages/NG9096litew.rst

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: PoE Designs

   pages/SJ2096POE.rst
   pages/SJ2088POE.rst
   pages/NG9097s2.rst
   pages/NG9097w.rst
   pages/NG9097pro.rst
   pages/NG9097prow.rst

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: Modular Cameras

   pages/DM3390.rst
   pages/DD2090.rst
   pages/DM1090.rst
   pages/BG0250TG.rst
   pages/BG0249.rst
   pages/DM0260imx582.rst
   pages/ffc-cameras.rst

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: System on Module

   pages/BW1099.rst
   pages/BW2099.rst
   pages/DM3399.rst

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: Miscellaneous Designs

   pages/DM1097.rst
   pages/DM2097.rst
   pages/DM6010.rst

# Baylibre ACME build repo manifests

` mkdir ~/ACME && cd ACME`

## Build for production ##

` repo init -u git@github.com:mtitinger/acme-manifests.git -m production.xml`

## Build for dev with IIO version ##

` repo init -u git@github.com:mtitinger/acme-manifests.git -m sigrok-iio.xml`

Remember to ` repo sync`


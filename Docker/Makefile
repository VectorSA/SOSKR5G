.PHONY: build-all
build-all: build-baza build-amf build-ausf build-nrf build-nssf build-pcf build-smf build-udm build-udr build-upf
build-baza:
	docker build --tag baza baza
build-amf: build-baza
	docker build --tag amf amf
build-ausf: build-baza
	docker build --tag ausf ausf
build-nrf: build-baza
	docker build --tag nrf nrf
build-nssf: build-baza
	docker build --tag nssf nssf
build-pcf: build-baza
	docker build --tag pcf pcf
build-smf: build-baza
	docker build --tag smf smf
build-udm: build-baza
	docker build --tag udm udm
build-udr: build-baza
	docker build --tag udr udr
build-upf: build-baza
	docker build --tag upf upf

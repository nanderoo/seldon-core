

build_images:
	s2i build -E environment_rest_v1 . seldonio/seldon-core-s2i-python3:0.3 seldonio/fixed-model:0.1
	s2i build -E environment_rest_v2 . seldonio/seldon-core-s2i-python3:0.3 seldonio/fixed-model:0.2

push_images:
	docker push seldonio/fixed-model:0.1
	docker push seldonio/fixed-model:0.2


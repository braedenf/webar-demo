<a-scene
	vr-mode-ui="enabled: false"
	embedded
	arjs="sourceType: webcam; sourceWidth: 1280; sourceHeight: 960; displayWidth: 1280; displayHeight: 960; debugUIEnabled: false; "
>
	<a-camera gps-camera rotation-reader />
	<a-entity
		gltf-model="/assets/magnemite/scene.gltf"
		rotation="0 180 0"
		scale="0.15 0.15 0.15"
		gps-entity-place="longitude: -36.8676046; latitude: 174.7270973"
		animation-mixer
	/>
</a-scene>

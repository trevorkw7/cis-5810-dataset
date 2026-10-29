# CIS 5810 Dataset

- `dataset/train_high/`: 62 frames from a high-elevation orbit of the tabletop scene (mug, bottle, BB-8).
- `dataset/test_low/`: 85 frames from a low-elevation orbit of the same scene, blind test set.
- `dataset/synthetic_low/`: 108 low-elevation views rendered from a Gaussian splat trained on `train_high`.
- `dataset/tracking_orbit/`: 67 frames (2 fps, 4K) from a handheld high-elevation orbit of the rearranged scene with an AprilTag on the placemat.
- `dataset/tracking_fixed/`: fixed-camera clip of the same scene (1080p, 30 fps, original file, location removed); the mug, bottle and BB-8 are moved by hand during the clip.
- AprilTag: tag36h11, ID 0, 100 mm black square.

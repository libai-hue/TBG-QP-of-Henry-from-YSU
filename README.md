# Robot Placement and Relative Pose Estimation

Supplementary materials for a robotic placement study, including a Panda–DEX-EE placement simulation and a MATLAB demonstration of ArUco-based relative pose estimation.

<img src="https://github.com/user-attachments/assets/bbc1bbf1-ef0e-4902-8760-3fbe00c2611f" alt="Panda–DEX-EE arm–hand assembly" width="800" />

## Contents

| Material | Description |
| --- | --- |
| [Panda–DEX-EE placement video](panda_dexee_platform_placement_0-6s.mp4) | A 0–6 s MuJoCo simulation of robot placement using an earlier TBG–QP controller. This is a simulation, not a hardware experiment. |
| [MATLAB relative-pose video](MATLAB%20realtime%20relative%20pose%20%28LIVE%29.mp4) | A demonstration of real-time relative pose estimation in MATLAB. |
| [ArUco relative-pose package](aruco-realtime-pose.zip) | MATLAB code, a sample image, configuration files, and documentation for estimating the relative pose of two ArUco markers. |

GitHub may not preview the videos on the file pages. Use the download button on the corresponding page to view them locally.

## Scope of the materials

The ArUco package is a relative-pose estimation demonstration. The placement video is a record from an earlier TBG–QP simulation. The current repository does not contain the complete controller and simulation code needed to reproduce the paper's numerical results. The two videos should not be interpreted as a single integrated hardware experiment.

## ArUco package: getting started

1. Download and extract [`aruco-realtime-pose.zip`](aruco-realtime-pose.zip).
2. Read the `README.md` inside the extracted folder for configuration, usage, and known limitations.
3. For an image-based demonstration, run `DEMO.bat` on Windows or `bash run_mac.sh` from the extracted folder on macOS/Linux.

The package documentation lists MATLAB R2018b or later and Image Processing Toolbox as requirements. Live camera acquisition requires Windows, a supported Daheng Galaxy camera, and a separately obtained Galaxy SDK. The default camera intrinsics are nominal; calibrate the camera before using the output for measurements.

## Citation

Publication details will be added when available. Until then, the repository can be referenced as:

> libai-hue, *TBG-QP-of-Henry-from-YSU*, GitHub repository. https://github.com/libai-hue/TBG-QP-of-Henry-from-YSU

## License

No repository-wide license file is currently provided. The ArUco package also documents third-party dependencies and their separate licensing considerations.

# Abrar Shahriar

I build latency-sensitive computer-vision, GPU-media, and real-time XR systems
from prototype to production. Based in Tokyo, I have more than five years of
experience delivering applied AI/ML and software across IoT, automotive,
digital twins, and interactive 3D.

## Production impact

- Converted human-pose-estimation components from Python to C/C++ for 2-3x
  speed-ups.
- Built and optimized GStreamer and NVIDIA DeepStream pipelines across
  multicore and GPU systems.
- Designed CCTV person re-identification pipelines and their evaluation tools.
- Integrated NVIDIA Omniverse Audio2Face with Unreal Engine 5 and tuned Lumen
  for real-time avatar applications.

Most of this production work is private. The public projects below show how I
approach platform constraints, performance, architecture, and delivery.

## Selected work

### [OmaWrite for Windows](https://github.com/AbrarZShahriar/omawrite-windows)

`C++` `Qt Quick` `Windows` `GitHub Actions`

A native Windows distribution of the focused OmaWrite Markdown editor. The
fork adds a reproducible Windows build, a one-click installer, a portable x64
package, file-association support, automated tests, release checksums, and
public CI-built binaries.

**Engineering evidence:** preserved the upstream Linux path while replacing
Linux-only assumptions at the Windows boundary, then automated the MSVC/Qt
build, runtime deployment, tests, packaging, and release verification.

### [Kodawari Engine](https://github.com/AbrarZShahriar/Kodawari-Engine)

`C++` `Vulkan` `SDL2` `ImGui`

An experimental tower-defense renderer built while studying Vulkan engine
architecture. It includes mesh rendering, SPIR-V shaders, an ImGui debug
interface, and data-oriented entity experiments. Its CMake build is verified
in GitHub Actions.

**Engineering evidence:** low-level graphics integration, explicit data and
resource lifetimes, shader tooling, and repair of a historical prototype into
a reproducible build.

### [Rizz Activity Tracker](https://github.com/AbrarZShahriar/rizz-v4-ken)

`TypeScript` `React Native` `Expo` `Supabase`

An offline-first mobile activity and goal tracker with authentication,
statistics, English and Japanese localization, and queued synchronization.

**Engineering evidence:** local-first interaction, explicit offline and
reconnection behavior, authenticated cloud persistence, and a documented
boundary between UI state, device storage, and Supabase.

### [House Prices regression study](https://github.com/AbrarZShahriar/house-prices-tensorflow-2019)

`Python` `TensorFlow` `scikit-learn` `Jupyter`

A 2019 feature-engineering and neural-network study for Kaggle's House Prices
competition. The final TensorFlow model recorded a score of `0.11694` and a
top-15.6% position at the time of submission.

**Engineering evidence:** an inspectable 2019 development record covering
feature engineering, preprocessing, training, and submission results.

## Operating range

- **Real-time ML:** Python, PyTorch, TensorFlow, ONNX Runtime, OpenCV,
  GStreamer, and NVIDIA DeepStream.
- **Native and graphics:** C++, C, C#, Qt, Vulkan, SDL2, CMake, and Windows and
  Linux development.
- **Interactive systems:** Unreal Engine 5, Unity, XR, real-time avatars,
  point clouds, and digital twins.
- **Delivery:** GPU and multicore profiling, reproducible builds, installers,
  public CI, Azure, and AWS.

## Contact

- [Portfolio](https://sites.google.com/view/portfolioshahriar/home)
- [LinkedIn](https://www.linkedin.com/in/abrar-shahriar-4a7483154/)
- [Email](mailto:a.zshahriar@gmail.com)
- [X / Twitter](https://x.com/AbrarZShahriar)

If you own a product in this space and need someone who can take it from an
uncertain prototype to a working release, contact me directly.

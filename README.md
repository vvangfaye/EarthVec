# EarthVec
[中文](README_zh-CN.md) | English

A repository for vectorizing Earth remote sensing imagery, featuring datasets, methods, and deployment tools.

## Overview

EarthVec aims to provide a repo for interpreting remote sensing imagery into vector formats, including polygons(such as building) and lines(such as road).

Currently under active development, EarthVec is starting with initial support for selected methods and datasets, with plans to expand its capabilities over time.

## Roadmap
Polygon vectorization methods and datasets are the initial focus of EarthVec. The following features are planned for future releases:
- [x] Add [HoliTracer](https://www.github.com/vvangfaye/HoliTracer) method.
- [x] Support large-size image training and inference.
- [x] Support raster formats with coordinate information.
- [ ] Improve documentation and usage processes (coming soon).
- [ ] Add [Hisup](https://github.com/SarahwXU/HiSup), [FFL](https://github.com/Lydorn/Polygonization-by-Frame-Field-Learning) methods (coming soon).
- [ ] Support patch-based datasets, and more methods.
- [ ] Add deployment tools and scripts.

Further roadmap: Line vectorization methods and datasets support.

## Setup Instructions
```bash
git clone https://github.com/vvangfaye/EarthVec.git
cd EarthVec
pip install -e . # install with editable mode
```

## Contributing
This project is in its early stages—contributions are welcome! Feel free to submit issues, feature requests, or connect with me directly (📧 email: wangfaye@whu.edu.cn).

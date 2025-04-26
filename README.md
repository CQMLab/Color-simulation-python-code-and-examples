# Thin-films-Color-simulation

> 🇺🇸 English Version

Thin-films-Color-simulation is a Python-based project developed to simulate the **color of multilayer thin films** by considering optical properties such as reflectance, transmittance, attenuation, and interference effects.

## Features
- Calculates the reflectance spectrum in the visible range based on complex refractive indices
- Converts the reflectance data to CIE XYZ color space using color matching functions
- Further converts CIE XYZ to sRGB color space through a transformation matrix and gamma compression
- Supports various multilayer structures, exemplified by SiO₂/Si, SnO₂/SiO₂/Si, and ZnO/SiO₂/Si

## Folder Structure
```
/DATA
  ├── CIE_cc_1931_2deg_cvrl.csv       (Color matching functions)
  ├── D65_step_1.csv                  (White reference)
  ├── Si n k.csv                      (n and k values of Si)
  ├── SiO2 n.csv                      (Refractive index of SiO₂)
  ├── SnO2 n.csv                      (Refractive index of SnO₂)
  ├── SnO2 k.csv                      (Extinction coefficient of SnO₂)
  ├── ZnO n Aguilar.csv               (Refractive index of ZnO)
  ├── ZnO k Aguilar.csv               (Extinction coefficient of ZnO)
```

## Usage
You can run the simulation using the provided Jupyter notebooks (`Thin-films-Color-simulation.ipynb`) or Python scripts.
Examples include structures such as SiO₂/Si, SnO₂/SiO₂/Si, and ZnO/SiO₂/Si.
For theoretical background and implementation details, see the citation section below.

## Citation

If you find this code useful, please cite:

> Dongik Lee and Seunghun Lee, **Color simulation of Multilayered Thin Films Using Python**, *Advances Sciences* (accepted, the link to be updated) (2025).  
> Preprint on ArXiv: [https://doi.org/10.48550/arXiv.2412.12828](https://doi.org/10.48550/arXiv.2412.12828)

This work also provides ample background on the underlying physics and implementation,  
*from basic electrodynamics (including the Fresnel equations) to the conversion of reflectance spectra to RGB values using a color matching function.*

## Contact

If you have any questions, suggestions, or issues regarding this project, please feel free to contact us at:

📧 pknu.cqmlab@gmail.com


---


# 박막 색상 시뮬레이션

> 🇰🇷 한글 버전

Thin-films-Color-simulation은 **다층 박막(multilayer thin films)** 의 색상을 시뮬레이션하기 위해 개발된 Python 기반 프로젝트입니다.  
반사율(reflectance), 투과율(transmittance), 감쇠(attenuation), 간섭(interference) 효과 등 다양한 광학적 특성을 고려하여 계산을 수행합니다.

## 주요 기능
- 복소 굴절률(complex refractive indices)을 기반으로 가시광선 영역의 반사 스펙트럼 계산
- 반사 데이터를 색상 매칭 함수(color matching functions)를 이용하여 CIE XYZ 색공간으로 변환
- 변환 행렬과 감마 보정을 통해 CIE XYZ를 sRGB 색공간으로 변환
- SiO₂/Si, SnO₂/SiO₂/Si, ZnO/SiO₂/Si 등의 다양한 다층 박막 구조 지원

## 폴더 구조
```
/DATA
  ├── CIE_cc_1931_2deg_cvrl.csv       (색상 매칭 함수)
  ├── D65_step_1.csv                  (D65 백색 기준)
  ├── Si n k.csv                      (Si의 n 및 k 값)
  ├── SiO2 n.csv                      (SiO₂의 굴절률)
  ├── SnO2 n.csv                      (SnO₂의 굴절률)
  ├── SnO2 k.csv                      (SnO₂의 소멸계수)
  ├── ZnO n Aguilar.csv               (ZnO의 굴절률)
  ├── ZnO k Aguilar.csv               (ZnO의 소멸계수)
```

## 사용 방법
제공된 주피터 노트북(`Thin-films-Color-simulation.ipynb`) 또는 Python 스크립트를 실행하여 시뮬레이션을 수행할 수 있습니다.  
예시로는 SiO₂/Si, SnO₂/SiO₂/Si, ZnO/SiO₂/Si 구조가 포함되어 있습니다.  
이론적 배경 및 구현 방법에 대한 자세한 내용은 아래의 인용(Citation) 섹션을 참고해 주세요.

## 인용

본 코드를 사용하셨다면 다음 논문을 인용해 주세요:

> Dongik Lee and Seunghun Lee, **Color simulation of Multilayered Thin Films Using Python**, *Advances Sciences* (accepted, 링크 업데이트 예정) (2025).  
> Preprint on ArXiv: [https://doi.org/10.48550/arXiv.2412.12828](https://doi.org/10.48550/arXiv.2412.12828)

본 연구는 기본적인 전자기학(electrodynamics) 이론(예: 프레넬 방정식(Fresnel equations))부터  
반사 스펙트럼을 색상 매칭 함수를 이용하여 RGB 값으로 변환하는 과정에 이르기까지,  
기초 물리 및 구현 방법에 대한 충분한 배경 설명도 함께 제공합니다.

## 문의

본 프로젝트에 대한 질문, 제안사항, 또는 문제가 있으시면 언제든지 아래 이메일로 연락해 주세요:

📧 pknu.cqmlab@gmail.com


---

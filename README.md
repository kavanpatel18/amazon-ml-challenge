<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=160&section=header&text=Amazon%20ML%20Challenge&fontSize=38&fontColor=fff&animation=twinkling&desc=Product%20Entity%20Extraction%20from%20Images&descSize=16&descAlignY=75" width="100%"/>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

</div>

## 🏆 Overview

Competition solution for the **Amazon ML Challenge** — extracting product entity values (weight, dimensions, voltage, etc.) directly from product images using multimodal ML. This is a real-world industry problem at massive scale.

## 🎯 Problem Statement

Given a product image, extract structured entity values like:
- item_weight: "2.5 kilogram"  
- item_volume: "100 millilitre"
- oltage: "220 volt"
- wattage: "1500 watt"

## ✨ Approach

- 🔍 **OCR pipeline** — extract text from product images
- 🧠 **NLP + regex** — parse and normalize entity values
- 🏅 **Leaderboard submission** — optimized CSV output format
- 📊 **Top-score submission** included in repo

## 🏗️ Project Structure

| Path | Description |
|------|-------------|
| 
otebooks/ | Experimentation & model notebooks |
| submission_top-score.csv | Best leaderboard submission |
| leaderboard/ | Score tracking |
| Amazon ML Challenge.pdf | Official problem statement |

## 🚀 Quick Start

`ash
git clone https://github.com/kavanpatel18/amazon-ml-challenge
cd amazon-ml-challenge
pip install torch transformers pandas numpy pillow
jupyter notebook notebooks/
`

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=80&section=footer&animation=twinkling" width="100%"/>
</div>
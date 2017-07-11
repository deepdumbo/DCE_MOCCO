# DCE_MOCCO
Direct model-based reconstruction of TK maps for accelerated DCE-MRI using a flexible MOCCO approach.

## Demo data
please download demo phantom data from: https://drive.google.com/file/d/0B4nLrDuviSiWT3ZKUmd0YjRwUEU/view?usp=sharing \n
please download demo in-vivo data from: https://drive.google.com/file/d/0B4nLrDuviSiWXzJhLWFwN1c1ZG8/view?usp=sharing 

## Demo scripts
**phantom_etofts_demo.m:**
Read pre-calculated eTofts TK maps and generated k-space (ref Yannick's work), and perform MOCCO to reconstruct TK maps from under-sampled data.
Option to select different TK solver: 1. Third-party Rocketship. 2. In-house gradient solver.

**AIF_TK_patlak_demo.m:**
Read in-vivo DCE MRI data, and retrospective under-sample the data by GOCART. Perform MOCCO to jointly reconstruct both AIF and patlak TK maps from under-sampled data. 

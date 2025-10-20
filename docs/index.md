Maximize Outer withg grid
py -3.11 sofa_optimize.py --method grid   --r-min 0.10 --r-max 0.70   --max-evals 400   --dx 0.02 --dy 0.02 --dtheta-deg 2.0 --ds 0.03   --outdir out   --video best.mp4   --save-json best.json  --video-as-success

 py -3.11 sofa_optimize.py --method grid   --r-min 0.45 --r-max 0.45   --max-evals 1   --dx 0.02 --dy 0.02 --dtheta-deg 2.0 --ds 0.03   --outdir out
 --video circle045.mp4   --save-json circle045.json   --video-as-success
it spends 336s to finish 

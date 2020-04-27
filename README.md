## Age prediction from faces

## Networks (Results)

- resnet34 pretrained + adamW+ wd = 1e-3, MSEflat
    - 6.671485 (mae)
- resnet50 pretrained + adamW+ wd = 1e-3, MSEflat
    - a little worse somehow :/
- resnet50 pretrained + adamW+ wd = 1e-3, L1flat (smooth L1)
    - works but not that great
    
## Conclusion
- adamW, mse is great combo
- bigger networks could overfit
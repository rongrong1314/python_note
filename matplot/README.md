# matplot
python画图笔记

### 画二维、三维线段
    - from mpl_toolkits.mplot3d import axes3d
    - import matplotlib.pyplot as plt
    - fig = plt.figure()
    - ax = fig.gca()#二维
    - ax = fig.gca(projection='3d')#三维
    - x = [0, 100],y = [0, 200],z = [0, 300]#给出点（0，0，0）和（100，200，300）
    - ax.plot (x,y,'red',alpha=1)#二维
    - ax.plot (x,y,z,'red',alpha=1)#三维

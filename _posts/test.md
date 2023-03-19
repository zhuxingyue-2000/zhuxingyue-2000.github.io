# test

# 图片

![logo.jpg](test%204f26c25004f94fedb98a5f785d7154f4/logo.jpg)

![logo.jpg](test%204f26c25004f94fedb98a5f785d7154f4/logo%201.jpg)

![small_logo.png](test%204f26c25004f94fedb98a5f785d7154f4/small_logo.png)

文字

# 代码

```jsx
figure(1);
subplot(2, 1, 1);

plot(num1,X_UCL1_list,'color',red,'LineWidth',1);
hold on;
plot(num1,X_LCL1_list,'color',orange,'LineWidth',1);
hold on;
plot(num1,x_mean1_list,'color',yellow,'LineWidth',1);
hold on;
plot(num1,X1,'-o','color',blue,'LineWidth',3);
lgd1_1=legend('UCL=23.924','LCL=23.878','均值=23.901','样本均值');
lgd1_1.NumColumns = 4;
title('均值控制图');
xlabel('样本序号');
ylabel('样本均值（mm）');
```
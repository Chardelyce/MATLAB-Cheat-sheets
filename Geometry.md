# MATLAB Geometry Cheat Sheet 

| Task                                           | MATLAB Command                          | Example                               |
|-----------------------------------------------|----------------------------------------|---------------------------------------|
| **Basic Geometry**                            |                                        |                                       |
| Calculate Area of a Rectangle                 | `area = length * width;`               | `length = 5; width = 3;`              |
| Calculate Perimeter of a Rectangle            | `perimeter = 2 * (length + width);`    | `length = 5; width = 3;`              |
| Calculate Area of a Circle                    | `area = pi * radius^2;`               | `radius = 4;`                         |
| Calculate Circumference of a Circle           | `circumference = 2 * pi * radius;`    | `radius = 4;`                         |
| Calculate Area of a Triangle                  | `area = 0.5 * base * height;`         | `base = 6; height = 8;`               |
| Calculate Perimeter of a Triangle             | `perimeter = a + b + c;`              | `a = 3; b = 4; c = 5;`                |
| **Graph Types**                               |                                        |                                       |
| Scatter Plot                                  | `scatter(x, y);`                      | `x = [1, 2, 3, 4]; y = [10, 15, 7, 5];` |
| Line Plot                                     | `plot(x, y);`                         | `x = 1:0.1:10; y = sin(x);`          |
| Bar Chart                                     | `bar(x, y);`                          | `x = [1, 2, 3, 4]; y = [10, 15, 7, 5];` |
| Histogram                                     | `hist(data, bins);`                   | `data = randn(1000, 1);`             |
| Pie Chart                                     | `pie(data, labels);`                  | `data = [30, 40, 20, 10];`           |
| **3D Plots**                                  |                                        |                                       |
| 3D Scatter Plot                              | `scatter3(x, y, z);`                  | `x = rand(100, 1); y = rand(100, 1); z = rand(100, 1);` |
| 3D Line Plot                                 | `plot3(x, y, z);`                     | `x = 1:0.1:10; y = sin(x); z = cos(x);` |
| 3D Surface Plot                              | `surf(X, Y, Z);`                      | `[X, Y] = meshgrid(-2:0.1:2); Z = X.^2 + Y.^2;` |
| **Annotations**                               |                                        |                                       |
| Label Axes                                    | `xlabel('X-axis Label'); ylabel('Y-axis Label');` |                                       |
| Title                                         | `title('Plot Title');`                |                                       |
| Legend                                        | `legend('Data 1', 'Data 2');`         |                                       |
| Text Annotation                               | `text(x, y, 'Text');`                 | `x = 2; y = 15;`                      |
| Arrow Annotation                              | `annotation('arrow', [x1, x2], [y1, y2]);` | `x1 = 2; y1 = 10; x2 = 4; y2 = 10;` |
| **Exporting Figures**                         |                                        |                                       |
| Save Figure as PNG                            | `saveas(gcf, 'figure.png');`          |                                       |
| Export Figure to PDF                          | `print('figure.pdf', '-dpdf');`       |                                       |

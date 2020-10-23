# OnBoardSwiftUI
This project can be used for implementation of OnBoarding Screen with help of SwiftUI



### GeometryReader for ImageCarouselView
```
GeometryReader { geometry in
                ImageCarouselView(numberOfImages: 3) {
                    Image("eagle")
                        .resizable()
                        .scaledToFill()
                        .frame(width: geometry.size.width, height: geometry.size.height)
                        .clipped()
                    Image("tiger")
                        .resizable()
                        .scaledToFill()
                        .frame(width: geometry.size.width, height: geometry.size.height)
                        .clipped()
                    Image("wolf")
                        .resizable()
                        .scaledToFill()
                        .frame(width: geometry.size.width, height: geometry.size.height)
                        .clipped()
                }
            }.frame(height: 890, alignment: .center)
```

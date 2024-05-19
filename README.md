<!-- *********************************************************************** -->
<!--                                                                         -->
<!--                                                      :::      ::::::::  -->
<!-- README.md                                          :+:      :+:    :+:  -->
<!--                                                  +:+ +:+         +:+    -->
<!-- By: chenxu <chenxu@mail.ustc.edu.cn>           +#+  +:+       +#+       -->
<!--                                              +#+#+#+#+#+   +#+          -->
<!-- Created: 2024/05/20 07:23:42 by chenxu            #+#    #+#            -->
<!-- Updated: 2024/05/20 07:29:48 by chenxu           ###   ########.fr      -->
<!--                                                                         -->
<!-- *********************************************************************** -->

# Map of China for ROOT(cern) users

```cpp
{
TFile * fMap = new TFile("ChinaMap.root");
TMultiGraph *mg = (TMultiGraph *)fMap->Get("map");
mg->Draw("l");
}
```

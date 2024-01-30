



# PDAC-cytology


**PDAC-cytology for pathology atlas repositories**




```
r language PDAC-cytology, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis pankreas adenokarsinom sitoloji TR, echo = (language == "TR")
## PDAC-cytology - pankreas adenokarsinom sitoloji {#sec-PDAC-cytology }
```


```
asis pancreas adenocarcinoma cytology EN, echo = (language == "EN")
## PDAC-cytology - pancreas adenocarcinoma cytology {#sec-PDAC-cytology }
```






```
r PDAC-cytology screenshot DQ, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/thumbnail_PDAC-cytology-DQ.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/PDAC-cytology/DQ.html",
  file = "./screenshots/thumbnail_PDAC-cytology-DQ.png"
)
}
```





::::: panel-tabset


### WSI - Link










[https://images.patolojiatlasi.com/PDAC-cytology/DQ.html](https://images.patolojiatlasi.com/PDAC-cytology/DQ.html)





```
asis, echo = (language == "TR")

**pankreas adenokarsinom sitoloji**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/thumbnail_PDAC-cytology-DQ.png){width="25%"}](https://images.patolojiatlasi.com/PDAC-cytology/DQ.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/PDAC-cytology/DQ.html)
```

```
asis, echo = (language == "EN")

**pancreas adenocarcinoma cytology**

[![Click for Full Screen WSI](./screenshots/thumbnail_PDAC-cytology-DQ.png){width="25%"}](https://images.patolojiatlasi.com/PDAC-cytology/DQ.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/PDAC-cytology/DQ.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/PDAC-cytology/DQ.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/PDAC-cytology/DQ.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

pankreas adenokarsinom sitoloji

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

pancreas adenocarcinoma cytology

:::

```









:::::













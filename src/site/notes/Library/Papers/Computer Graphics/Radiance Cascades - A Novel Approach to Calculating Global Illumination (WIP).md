---
{"aliases":["Radiance Cascades"],"Author":"Alexander Sannikov","Status":"backlog","dg-publish":true,"dg-note-icon":"stone","title":"Radiance Cascades: A Novel Approach to Calculating Global Illumination [WIP]","permalink":"/library/papers/computer-graphics/radiance-cascades-a-novel-approach-to-calculating-global-illumination-wip/","dgPassFrontmatter":true,"noteIcon":"stone","created":"","updated":""}
---

source: https://drive.google.com/file/d/1L6v1_7HY2X-LV3Ofb6oyTIxgEaP4LOI6/view

(*not yet published*)
Citation:
Alexander Sannikov, Radiance Cascades, Journal of Computer Graphics Techniques (JCGT),
vol. vol, no. issue, 1–1, year
http://jcgt.org/published/vol/issue/num/

<iframe src="https://drive.google.com/file/d/1L6v1_7HY2X-LV3Ofb6oyTIxgEaP4LOI6/preview" width="640" height="480" allow="autoplay"></iframe>
## Abstract
This work proposes a novel data structure called radiance cascades that allows effectively
storing and calculating radiance field by decomposing it into multiple ranges (from near-field to far-field) and storing them separately. The idea of radiance cascades relies on an observa-
tion, that in order to resolve radiance emitted by an object, one needs to have higher linear resolution next to it, and higher angular resolution farther away from it. Radiance cascades exhibit a distinctly unique way of asymptotic scaling that for all practical purposes is equiva-
lent to casting infinitely many rays in a finite amount of time, while using a finite amount of memory. This highly unusual property allows to effectively remove the total number of rays
as the primary constraint for calculating global illumination in 2d and 3d.
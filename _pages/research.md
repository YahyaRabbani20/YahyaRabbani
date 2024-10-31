---
layout: "single"
title: ""
permalink: "/research/"
author_profile: true

---

<script type="text/javascript">
   function toggleVisibility(block_id) {
       var e = document.getElementById(block_id);
       if(e.style.display == 'block')
          e.style.display = 'none';
       else
          e.style.display = 'block';
   }
    function copyToClip(element) {
        var str = document.getElementById(element).innerHTML;
        function listener(e) {
            e.clipboardData.setData("text/html", str);
            e.clipboardData.setData("text/plain", str);
            e.preventDefault();
        }
        document.addEventListener("copy", listener);
        document.execCommand("copy");
        document.removeEventListener("copy", listener);
};
</script>

# Publications

## For a complete list of publications, please refer to my [Google Scholar](https://scholar.google.com/citations?user=oM63nTMAAAAJ&hl=en) page.


## PhD Thesis

# Models of diachronic semantic change using word embeddings
<normal>
    <a href="https://www.theses.fr/2021UPASG006/abes" style="color:page.header.overlay_color">[PDF]</a>
    <a style="color:page.header.overlay_color; cursor: pointer; cursor: hand;" onclick="toggleVisibility('bib_thesis');">[BibTeX]</a>
</normal>
<div id="bib_thesis" style="display:none;">
<small>
<a class="btn"  onclick="copyToClip('bib_thesis');">copy to clipboard</a>
<div class="highlighter-rouge"><pre id="bib_thesis" class="highlight">
@phdthesis{montariol2021models,
  title={Models of diachronic semantic change using word embeddings},
  author={Montariol, Syrielle},
  year={2021},
  school={Universit{\'e} Paris-Saclay}
}
</pre></div></small>
</div>


## 2021

# Measure and Evaluation of Semantic Divergence across Two Languages
*S Montariol and A Allauzen*  
2021 Conference of the Association for Computational Linguistics (ACL 2021)
<normal>
    <a href="https://arxiv.org/pdf/2001.06629.pdf" style="color:page.header.overlay_color">[PDF]</a>
    <a style="color:page.header.overlay_color; cursor: pointer; cursor: hand;" onclick="toggleVisibility('bib_acl21');">[BibTeX]</a>
</normal>
<div id="bib_acl21" style="display:none;">
<small>
<a class="btn"  onclick="copyToClip('bib_acl21');">copy to clipboard</a>
<div class="highlighter-rouge"><pre id="bib_acl21" class="highlight">
@inproceedings{montariol-allauzen-2021-measure,
    title = "Measure and Evaluation of Semantic Divergence across Two Languages",
    author = "Montariol, Syrielle  and
      Allauzen, Alexandre",
    booktitle = "Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 1: Long Papers)",
    month = aug,
    year = "2021",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.acl-long.100",
    doi = "10.18653/v1/2021.acl-long.100",
    pages = "1247--1258",
}

</pre></div></small>
</div>


# Scalable and interpretable semantic change detection
*S Montariol, M Matej and L Pivovarova*  
2021 Conference of the North American Chapter of the Association for Computational Linguistics (NAACL 2021)
<normal>
    <a href="https://aclanthology.org/2021.naacl-main.369.pdf" style="color:page.header.overlay_color">[PDF]</a>
    <a href="https://github.com/matejMartinc/scalable_semantic_shift" style="color:page.header.overlay_color">[GitHub]</a>
    <a style="color:page.header.overlay_color; cursor: pointer; cursor: hand;" onclick="toggleVisibility('bib_naacl21');">[BibTeX]</a>
</normal>
<div id="bib_naacl21" style="display:none;">
<small>
<a class="btn"  onclick="copyToClip('bib_naacl21');">copy to clipboard</a>
<div class="highlighter-rouge"><pre id="bib_naacl21" class="highlight">
@inproceedings{montariol-etal-2021-scalable,
    title = "Scalable and Interpretable Semantic Change Detection",
    author = "Montariol, Syrielle  and
      Martinc, Matej  and
      Pivovarova, Lidia",
    booktitle = "Proceedings of the 2021 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies",
    month = jun,
    year = "2021",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.naacl-main.369",
    doi = "10.18653/v1/2021.naacl-main.369",
    pages = "4642--4652",
}

</pre></div></small>
</div>

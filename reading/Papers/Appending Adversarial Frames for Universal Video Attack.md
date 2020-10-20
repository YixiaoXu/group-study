**Title:** Appending Adversarial Frames for Universal Video Attack

**Source:** 

**Authors:** Zhikai Chen, Lingxi Xie, Shanmin Pang, Yong He, Qi Tian

---

**Summary**

According to this paper, basic adversarial video attack method which add perturbations to each original frames, has 4 main shortcomings:
1. High authority needed.
2. Unsafe. (Easy to percept because neighbor oringinal frames are related while adversarial perturbations are not)
3. High rate of perturbation
4. Weak transferibility

To improve the method, the paper raised a new model named Adding Adversarial Frames(AAF), which adds a few dummy frames with adversarial perturbations to original frames.

Meanwhile, the paper also provided severial variants of AAF in order to suits different situations including transferability among modules or videos.

The fool rate and AAP of the two methods mentiond abow proves that AAF has a better performance on perturbation rate and transferability, while a worse performance on targeted attack than the basic adversarial video attack methods.

---

**Strengthens**  

1.Lower perturbation rate.

2.Better transferability

---

**Weaknesses**  

1.Did not consider about time cost.

2.A bad performance on targeted attack.

---

**Comments**  

> The paper did not mention about the time cost to train the module, while time cost has became one of the most important things to considered about while training a module. 

---

---
Defined in [[9. The Language of First Order Logic]]

---
In the context of first order logic, terms are [[strings]] of symbols that represent elements.

The following are **terms**:
- All constant symbols $c_0, c_1, \dots$
- All variable symbols $v_0, v_1, \dots$
- Strings of the form $f_i(t_1,\dots,t_n)$ where $f_i$ is an $n$-ary function symbol and $t_1,\dots,t_n$ are terms.

As strings, terms can be formally considered to be tuples. There is a distinction between a symbol $s$ and the term constructed from that symbol, $\langle s\rangle$, but we will almost always drop the tuple notation for convenience. 

Nonetheless, there are situations were ambiguity may occur. An example can be found in [[12. Interpretation of Terms|lesson 12 (M125A)]], where truth value functions are initially defined on variables but then extended to work on terms.

Finally, note that terms do not have any interpretation on their own as they are still just a collection of symbols.
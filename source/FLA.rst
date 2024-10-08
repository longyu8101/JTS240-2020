附录A  打入桩可打性分析
=====================================

.. raw:: html

  <h2 id="test111">附录A  打入桩可打性分析</h2>

.. raw:: html

 <p style="text-align:justify"><a href="#idA.0.1"> A.0.1</a> <span id="idA.0.1"> 钢管桩、预制混凝土桩等打入桩打桩施工前，应根据地质条件、承载力要求、桩端设计高程、打桩锤参数等，分析基桩轴向极限承载力、总锤击数和终锤贯入度。</span></p>

 <p style="text-align:justify"><a href="#idA.0.2"> A.0.2</a> <span id="idA.0.2"> 基桩轴向极限承载力根据具体情况可采用承载力经验参数法或静力触探等方法确定；采用经验参数法估算基桩轴向极限承载力时，还应满足现行行业标准《码头结构设计规范》(JTS 167)的相关要求。</span></p>

 <p style="text-align:justify"><a href="#idA.0.3"> A.0.3</a> <span id="idA.0.3"> 可打性理论分析应符合下列要求。</span></p>
 <p style="text-align:justify"><a href="#idA.0.3.1"> A.0.3.1</a> <span id="idA.0.3.1"> 桩总锤击数和终锤贯入度宜采用考虑土阻力的一维波动方程，即式(<a href="#ideqA.0.3-1">式(A.0.3-1)</a><span id="ideqA.0.3-1">)进行分析，利用数值差分法求解，有条件时可采用基于考虑土阻力的一维波动方程的可打性分析软件，进行基桩的可打性分析。</span></p>

$$\\dfrac{\\partial ^{2} u}{\\partial x^{2}}=\\dfrac{1}{C}\\dfrac{\\partial ^{2} u}{\\partial t^{2}}+\\dfrac{1}{W\\cdot C^{2}} R\\tag{A.0.3-1}$$

.. raw:: html

 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中</td>
 <td width="30px" align='right' id="eqzs"><i>u</i></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">x处桩截面的质点位移(m)；</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>x</i></td>
 <td id="eqzs">——</td>
 <td id="eqzs">桩截面的位置坐标(m)；</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>t</i></td>
 <td id="eqzs">——</td>
 <td id="eqzs">时间(s)；</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>W</i></td>
 <td id="eqzs">——</td>
 <td id="eqzs">桩身质量(kg)；</td>
 </tr>
  <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>R</i></td>
 <td id="eqzs">——</td>
 <td id="eqzs">桩身土阻力(kN)；</td>
 </tr>
  <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>C</i></td>
 <td id="eqzs">——</td>
 <td id="eqzs">弹性应力波波速(m/s),<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>C</mi><mo>=</mo><mo stretchy="false">(</mo><mi>E</mi><mrow><mo>/</mo></mrow><mi>ρ</mi><msup><mo stretchy="false">)</mo><mrow><mfrac><mn>1</mn><mn>2</mn></mfrac></mrow></msup></math> ；</td>
 </tr>
  <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>E</i></td>
 <td id="eqzs">——</td>
 <td id="eqzs">桩身材料的弹性模量(kPa)；</td>
 </tr>
  <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>ρ</i></td>
 <td id="eqzs">——</td>
 <td id="eqzs">桩身材料的密度(t/m<sup>3</sup>)。；</td>
 </tr>
   </table>
 <p></p>   
 
 <p style="text-align:justify"><a href="#idA.0.3.2"> A.0.3.2</a> <span id="idA.0.3.2"> 解考虑土阻力的一维波动方程时，宜将桩锤—垫层—桩—土组成的打桩系统离散为质量块—弹簧—阻尼器模型。其中，桩锤、桩帽、垫层、锤垫、桩垫、桩身的弹性由无质量的弹簧模拟，各部分的质量由不可压缩的刚性块体模拟；桩周土的弹性极限静阻力和塑性动阻力用由弹簧、摩擦键、阻尼壶组成的土体流变模型模拟。</span></p>
 <p style="text-align:justify"><a href="#idA.0.3.3"> A.0.3.3</a> <span id="idA.0.3.3"> 桩身宜离散为N个长度为L<sub>i</sub>(i=1,2,…,N)的单元，每个单元由1个无质 量的弹簧、1个质量块、1个阻尼器组成，其中阻尼器可采用黏滞阻尼模型，见下列公式：</span></p>

$$L_{i}=a_{i}\\cdot L \\tag{A.0.3-2}$$

$$W_{i}=\\rho _{i}\\cdot A_{i}\\cdot  L_{i}\\tag{A.0.3-3}$$

$$k_{i}=E_{i}\\cdot A_{i}/ L_{i}\\tag{A.0.3-4}$$


.. raw:: html

 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中</td>
 <td width="30px" align='right' id="eqzs"><i>L</i><sub>i</sub></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">第i个桩单元长度(m),宜取<i>L</i><sub>i</sub>≤1 m,当需增加计算精度或桩身阻抗有变化时应适当减小<i>L</i><sub>i</sub>的取值；</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>a</i><sub>i</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">第i个桩单元长度乘子，<math xmlns="http://www.w3.org/1998/Math/MathML" ><munderover><mo data-mjx-texclass="OP">∑</mo><mrow><mi>i</mi><mo>=</mo><mn>1</mn></mrow><mrow><mi>N</mi></mrow></munderover><msub><mi>a</mi><mrow><mi>i</mi></mrow></msub><mo>=</mo><mn>1.0</mn></math>；</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>L</i></td>
 <td id="eqzs">——</td>
 <td id="eqzs">桩的总长度(m)；</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>W</i><sub>i</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">第i个桩单元质量(kg)；</td>
 </tr>
  <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>ρ</i><sub>i</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">第i个桩单元的材料密度(kg/m<sup>3</sup>)；</td>
 </tr>
  <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>A</i><sub>i</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">第i个桩单元横截面面积(m<sup>2</sup>)；</td>
 </tr>
  <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>k</i><sub>i</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">第i个桩单元刚度(kN/m)；</td>
 </tr>
  <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>E</i><sub>i</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">第i个桩单元桩身材料的弹性模量(kPa)。</td>
 </tr>    
   </table>
 <p></p>   

 <p style="text-align:justify"><a href="#idA.0.3.4"> A.0.3.4</a> <span id="idA.0.3.4"> 桩身土阻力应包括土静阻力和土动阻力。土的静阻力可采用无质量的弹簧表示，见<a href="#ideqA.0.3-5">式(A.0.3-5)</a><span id="ideqA.0.3-5">;土的动阻力计算可采用Smith标准阻尼模型，见<a href="#ideqA.0.3-6">式(A.0.3-6)</a><span id="ideqA.0.3-6">;计算结果需与现场打桩监控试验结果对照使用时，也可采用Casc 黏滞阻尼模型计算，见<a href="#ideqA.0.3-6">式(A.0.3-6)</a><span id="ideqA.0.3-6">。</span></p>
 
$$ \\begin{cases}R_{\\mathrm{si} }=\\dfrac{u_{\\mathrm{i}}}{q_{\\mathrm{i} }}Q_{\\mathrm{i} }\\qquad u_{\\mathrm{i} } \\leqslant q_{\\mathrm{i}} \\\\ R_{\\mathrm{si} }=Q_{\\mathrm{i} }\\qquad u_{\\mathrm{i} } > q_{\\mathrm{i}}\\end{cases}\\tag{A.0.3-5}$$

$$ R_{\\mathrm{di} }=j_{\\mathrm{si}}\\cdot \\left| R_{\\mathrm{si}} \\right |  \\cdot v_{\\mathrm{i} }\\tag{A.0.3-6}$$

$$ R_{\\mathrm{di} }=j_{\\mathrm{ci}}\\cdot  v_{\\mathrm{i} } \\cdot \\sqrt{Z_{\\mathrm{i} }} \\tag{A.0.3-7}$$


.. raw:: html

 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中</td>
 <td width="30px" align='right' id="eqzs"><i>R</i><sub>si</sub></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">i个桩单元的极限静土阻力(kN)；</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>u</i><sub>i</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">第i个桩单元的位移(m)；</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>Q</i><sub>i</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">第i个桩单元的极限侧摩阻力或端阻力(kN)；</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>q</i><sub>i</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">第i个桩单元桩侧或桩端土体弹限对应的位移(m),桩侧土可取<i>q</i><sub>i</sub>=2.5 mm,桩端土为软土时可取<i>q</i><sub>i</sub>= D/60,桩端土致密时可取<i>q</i><sub>i</sub>=D/120,D为桩径；</td>
 </tr>
  <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>R</i><sub>di</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">第i个桩单元的动土阻力(kN)；</td>
 </tr>
  <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>j</i><sub>si</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">第i个桩单元的 Smith 阻尼系数；</td>
 </tr>
  <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>ν</i><sub>i</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">第i个桩单元的速度(m/s)；</td>
 </tr>
  <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>j</i><sub>ci</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">第i个桩单元的Casc阻尼系数；</td>
 </tr> 
  <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>Z</i><sub>ci</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">第i个桩单元桩身截面力学阻抗(kN·s/m)。</td>
 </tr>      
   </table>
 <p></p>   
 
 
 
 <p style="text-align:justify"><a href="#idA.0.3.5"> A.0.3.5</a> <span id="idA.0.3.5"> 打桩锤宜简化为弹簧和质量块。根据锤芯的长度，可将柴油锤、液压锤或振动锤离散为M个长度为L(i=1,2,…,M)的单元，每个单元由1个无质量的弹簧和1个质量块组成，单元刚度和单元重力分别见<a href="#ideqA.0.3-8">式(A.0.3-8)</a><span id="ideqA.0.3-8">和<a href="#ideqA.0.3-9">式(A.0.3-9)</a><span id="ideqA.0.3-9">。</span></p>

$$ k_{\\mathrm{i} }=E^{'}_{\\mathrm{i} }\\cdot  A^{'}_{\\mathrm{i} } /{L^{'}_{\\mathrm{i} }} \\tag{A.0.3-8}$$

$$ W^{'}_{\\mathrm{i} }=\\gamma ^{'}_{\\mathrm{i} }\\cdot  A^{'}_{\\mathrm{i} } \\cdot {L^{'}_{\\mathrm{i} }} \\tag{A.0.3-9}$$

.. raw:: html

 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中</td>
 <td width="30px" align='right' id="eqzs"><i>k</i><sub>si</sub></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">第i个打桩锤单元刚度(kN/m)</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>E</i><sub>i</sub><sup>'</sup></td>
 <td id="eqzs">——</td>
 <td id="eqzs">第i个打桩锤单元材料的弹性模量(kPa)；</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>A</i><sub>i</sub><sup>'</sup></td>
 <td id="eqzs">——</td>
 <td id="eqzs">第i个打桩锤单元横截面面积(m<sup>2</sup>)；</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>L</i><sub>i</sub><sup>'</sup></td>
 <td id="eqzs">——</td>
 <td id="eqzs">第i个打桩锤单元长度(m),对于柴油锤和液压锤可取 <i>L</i><sub>i</sub><sup>'</sup>=1 m；</td>
 </tr>
  <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>W</i><sub>i</sub><sup>'</sup></td>
 <td id="eqzs">——</td>
 <td id="eqzs">第i个打桩锤单元重力(kN)；</td>
 </tr> 
  <tr>
 <td id="eqzs"> </td>
 <td align='right' id="eqzs"><i>γ</i><sub>i</sub><sup>'</sup></td>
 <td id="eqzs">——</td>
 <td id="eqzs">第i个打桩锤单元的材料重度(kN/m<sup>3</sup>)。</td>
 </tr>      
   </table>
 <p></p>   
 


 <p style="text-align:justify"><a href="#idA.0.3.6"> A.0.3.6</a> <span id="idA.0.3.6"> 打桩锤对桩的一次锤击可用应力波在桩锤—垫层—桩—土系统中传播所产生的波动分析。分析时宜将一次锤击时间分成若干个时间段<i> △t</i>,可取<i> △t</i>=(1/4000～1/3000) s。在<i> △t</i>时间内应力波仅在一个单元内运动，可做匀速运动处理，将问题转化为各分离单元的运动问题迭代计算。</span></p>
 <p style="text-align:justify"><a href="#idA.0.3.7"> A.0.3.7</a> <span id="idA.0.3.7"> 出现下列情况之一时可终止计算：</span></p>      
 <ol>
 <li>桩端贯入度即桩端单元的位移已达到最大值，不再增加；</li>
 <li>各单元的速度均已等于零或为负值；</li>
 <li>重复迭代计算次数已达到规定次数。</li>
 </ol>
 <p style="text-align:justify"><a href="#idA.0.4"> A.0.4</a> <span id="idA.0.4"> 存在施工间歇、不能连续施打的基桩的可打性分析，应考虑间歇期土阻力恢复的影响。</span></p>

 <p style="text-align:justify"><a href="#idA.0.5"> A.0.5</a> <span id="idA.0.5"> 管桩的可打性分析应考虑土塞作用对沉桩性状的影响，大直径管桩尚应考虑桩内侧土阻力对沉桩的影响。</span></p>

 <p style="text-align:justify"><a href="#idA.0.6"> A.0.6</a> <span id="idA.0.6"> 基桩的可打性分析结果宜与打桩过程监测结果对比分析。</span></p>

 <p style="text-align:justify"><a href="#idA.0.7"> A.0.7</a> <span id="idA.0.7"> 可打性分析报告应包括下列内容：</span></p>
 <ol>
 <li>基桩轴向承载力；</li>
 <li>桩身压应力和拉应力；</li>
 <li>终锤贯入度；</li>
 <li>基桩轴向承载力一贯入度曲线；</li>
 <li>总锤击数或振动下沉时间；</li>
 <li>桩身最大能量；</li>
 <li>打桩设备。</li>
 </ol>


:math:`\ ` 
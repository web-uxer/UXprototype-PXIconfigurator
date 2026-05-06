# NI/Emerson Header & Footer Component Package

This package contains all the code and assets needed to implement the NI/Emerson header and footer components.

## Table of Contents
1. [Component Files](#component-files)
2. [SVG Path Data](#svg-path-data)
3. [Image Assets](#image-assets)
4. [Usage Instructions](#usage-instructions)

---

## Component Files

### 1. Header Component (UseThisCopilot1.tsx)

```tsx
import svgPaths from "./svg-5hcqfb83f3";
import imgImage3 from "./4f2e2d6e530c5f967ea9d19fb66ca38cd6842529.png";
import { imgClipPath, imgClipPath1, imgClipPath2, imgClipPath3, imgClipPath4, imgClipPath5, imgClipPath6, imgClipPath7, imgClipPath8, imgClipPath9, imgClipPath10 } from "./svg-tq4kl";

function Layer1() {
  return (
    <div className="col-1 h-[8.124px] ml-0 mt-[20.07px] relative row-1 w-[67.233px]" data-name="Layer">
      <svg className="absolute block inset-0 size-full" fill="none" preserveAspectRatio="none" viewBox="0 0 67.2335 8.12394">
        <g id="Layer">
          <path clipRule="evenodd" d={svgPaths.p550dd20} fill="var(--fill-0, #004B8D)" fillRule="evenodd" id="Layer_2" />
          <path clipRule="evenodd" d={svgPaths.p27cb8a00} fill="var(--fill-0, #004B8D)" fillRule="evenodd" id="Layer_3" />
          <path d={svgPaths.pbbf8f00} fill="var(--fill-0, #004B8D)" id="Layer_4" />
          <path d={svgPaths.p135d1380} fill="var(--fill-0, #004B8D)" id="Layer_5" />
          <path d={svgPaths.p2e793a0} fill="var(--fill-0, #004B8D)" id="Layer_6" />
          <path d={svgPaths.p1657cb00} fill="var(--fill-0, #004B8D)" id="Layer_7" />
          <path d={svgPaths.p2cd30ef0} fill="var(--fill-0, #004B8D)" id="Layer_8" />
          <path d={svgPaths.pcb9b580} fill="var(--fill-0, #004B8D)" id="Layer_9" />
          <path d={svgPaths.p1414d080} fill="var(--fill-0, #004B8D)" id="Layer_10" />
        </g>
      </svg>
    </div>
  );
}

function ClipPath() {
  return (
    <div className="col-1 h-[14.488px] mask-alpha mask-intersect mask-no-clip mask-no-repeat mask-position-[3.562px_3.158px] mask-size-[7.209px_8.092px] ml-0 mt-0 relative row-1 w-[14.36px]" style={{ maskImage: `url('${imgClipPath}')` }} data-name="Clip-Path">
      <svg className="absolute block inset-0 size-full" fill="none" preserveAspectRatio="none" viewBox="0 0 14.3604 14.4875">
        <g id="Clip-Path">
          <path d={svgPaths.p34caf200} fill="url(#paint0_linear_1_3649)" id="Layer" />
        </g>
        <defs>
          <linearGradient gradientUnits="userSpaceOnUse" id="paint0_linear_1_3649" x1="3.435" x2="11.5768" y1="5.05578" y2="9.8109">
            <stop stopColor="#949698" />
            <stop offset="0.1" stopColor="#9FA1A3" />
            <stop offset="0.3" stopColor="#BCBEBF" />
            <stop offset="0.5" stopColor="#E7E8E9" />
            <stop offset="0.6" stopColor="#DDDEDF" />
            <stop offset="0.8" stopColor="#C2C3C5" />
            <stop offset="1" stopColor="#949698" />
          </linearGradient>
        </defs>
      </svg>
    </div>
  );
}

function Group2() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-[-3.56px] mt-[-3.16px] place-items-start relative row-1" data-name="Group">
      <ClipPath />
    </div>
  );
}

function ClipPathGroup() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-0 mt-0 place-items-start relative row-1" data-name="Clip path group">
      <Group2 />
    </div>
  );
}

function Layer2() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-[5.52px] mt-0 place-items-start relative row-1" data-name="Layer">
      <ClipPathGroup />
    </div>
  );
}

function ClipPath1() {
  return (
    <div className="col-1 h-[6.016px] mask-alpha mask-intersect mask-no-clip mask-no-repeat mask-position-[1.096px_1.791px] mask-size-[4.071px_2.438px] ml-0 mt-0 relative row-1 w-[6.228px]" style={{ maskImage: `url('${imgClipPath1}')` }} data-name="Clip-Path">
      <svg className="absolute block inset-0 size-full" fill="none" preserveAspectRatio="none" viewBox="0 0 6.22773 6.01649">
        <g id="Clip-Path">
          <path d={svgPaths.p133a4900} fill="url(#paint0_linear_1_3655)" id="Layer" />
        </g>
        <defs>
          <linearGradient gradientUnits="userSpaceOnUse" id="paint0_linear_1_3655" x1="1.1056" x2="5.17381" y1="1.83554" y2="4.20952">
            <stop stopColor="#949698" />
            <stop offset="0.2" stopColor="#9FA1A3" />
            <stop offset="0.6" stopColor="#BCBEBF" />
            <stop offset="1" stopColor="#E7E8E9" />
          </linearGradient>
        </defs>
      </svg>
    </div>
  );
}

function Group3() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-[-1.1px] mt-[-1.79px] place-items-start relative row-1" data-name="Group">
      <ClipPath1 />
    </div>
  );
}

function ClipPathGroup1() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-0 mt-0 place-items-start relative row-1" data-name="Clip path group">
      <Group3 />
    </div>
  );
}

function Layer3() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-[2.76px] mt-[6.25px] place-items-start relative row-1" data-name="Layer">
      <ClipPathGroup1 />
    </div>
  );
}

function ClipPath2() {
  return (
    <div className="col-1 h-[13.793px] mask-alpha mask-intersect mask-no-clip mask-no-repeat mask-position-[2.228px_4.333px] mask-size-[9.949px_5.086px] ml-0 mt-0 relative row-1 w-[14.407px]" style={{ maskImage: `url('${imgClipPath2}')` }} data-name="Clip-Path">
      <svg className="absolute block inset-0 size-full" fill="none" preserveAspectRatio="none" viewBox="0 0 14.4068 13.7934">
        <g id="Clip-Path">
          <path d={svgPaths.p37a89b00} fill="url(#paint0_linear_1_3617)" id="Layer" />
        </g>
        <defs>
          <linearGradient gradientUnits="userSpaceOnUse" id="paint0_linear_1_3617" x1="3.11286" x2="11.2797" y1="4.50655" y2="9.27956">
            <stop stopColor="#004786" />
            <stop offset="0.2" stopColor="#004786" />
            <stop offset="0.3" stopColor="#175490" />
            <stop offset="0.4" stopColor="#5076A9" />
            <stop offset="0.5" stopColor="#7289B7" />
            <stop offset="0.6" stopColor="#5B7CAD" />
            <stop offset="0.7" stopColor="#1A5691" />
            <stop offset="0.8" stopColor="#004786" />
            <stop offset="1" stopColor="#004786" />
          </linearGradient>
        </defs>
      </svg>
    </div>
  );
}

function Group4() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-[-2.23px] mt-[-4.33px] place-items-start relative row-1" data-name="Group">
      <ClipPath2 />
    </div>
  );
}

function ClipPathGroup2() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-0 mt-0 place-items-start relative row-1" data-name="Clip path group">
      <Group4 />
    </div>
  );
}

function Layer4() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-[2.77px] mt-[4.63px] place-items-start relative row-1" data-name="Layer">
      <ClipPathGroup2 />
    </div>
  );
}

function ClipPath3() {
  return (
    <div className="col-1 h-[6.02px] mask-alpha mask-intersect mask-no-clip mask-no-repeat mask-position-[1.091px_1.789px] mask-size-[4.072px_2.438px] ml-0 mt-0 relative row-1 w-[6.228px]" style={{ maskImage: `url('${imgClipPath3}')` }} data-name="Clip-Path">
      <svg className="absolute block inset-0 size-full" fill="none" preserveAspectRatio="none" viewBox="0 0 6.22759 6.02006">
        <g id="Clip-Path">
          <path d={svgPaths.p25a40600} fill="url(#paint0_linear_1_3626)" id="Layer" />
        </g>
        <defs>
          <linearGradient gradientUnits="userSpaceOnUse" id="paint0_linear_1_3626" x1="1.10202" x2="5.17023" y1="1.83375" y2="4.20952">
            <stop stopColor="#949698" />
            <stop offset="0.2" stopColor="#9FA1A3" />
            <stop offset="0.6" stopColor="#BCBEBF" />
            <stop offset="1" stopColor="#E7E8E9" />
          </linearGradient>
        </defs>
      </svg>
    </div>
  );
}

function Group5() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-[-1.09px] mt-[-1.79px] place-items-start relative row-1" data-name="Group">
      <ClipPath3 />
    </div>
  );
}

function ClipPathGroup3() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-0 mt-0 place-items-start relative row-1" data-name="Clip path group">
      <Group5 />
    </div>
  );
}

function Layer5() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-[1.38px] mt-[8.58px] place-items-start relative row-1" data-name="Layer">
      <ClipPathGroup3 />
    </div>
  );
}

function ClipPath4() {
  return (
    <div className="col-1 h-[14.391px] mask-alpha mask-intersect mask-no-clip mask-no-repeat mask-position-[3.548px_3.158px] mask-size-[7.205px_8.074px] ml-0 mt-0 relative row-1 w-[14.285px]" style={{ maskImage: `url('${imgClipPath4}')` }} data-name="Clip-Path">
      <svg className="absolute block inset-0 size-full" fill="none" preserveAspectRatio="none" viewBox="0 0 14.2853 14.3909">
        <g id="Clip-Path">
          <path d={svgPaths.p1db4f780} fill="url(#paint0_linear_1_3584)" id="Layer" />
        </g>
        <defs>
          <linearGradient gradientUnits="userSpaceOnUse" id="paint0_linear_1_3584" x1="2.74445" x2="10.8809" y1="4.62642" y2="9.37796">
            <stop stopColor="#949698" />
            <stop offset="0.1" stopColor="#9FA1A3" />
            <stop offset="0.3" stopColor="#BCBEBF" />
            <stop offset="0.5" stopColor="#E7E8E9" />
            <stop offset="0.6" stopColor="#DDDEDF" />
            <stop offset="0.8" stopColor="#C2C3C5" />
            <stop offset="1" stopColor="#949698" />
          </linearGradient>
        </defs>
      </svg>
    </div>
  );
}

function Group6() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-[-3.55px] mt-[-3.16px] place-items-start relative row-1" data-name="Group">
      <ClipPath4 />
    </div>
  );
}

function ClipPathGroup4() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-0 mt-0 place-items-start relative row-1" data-name="Clip path group">
      <Group6 />
    </div>
  );
}

function Layer6() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-0 mt-[10.91px] place-items-start relative row-1" data-name="Layer">
      <ClipPathGroup4 />
    </div>
  );
}

function ClipPath5() {
  return (
    <div className="col-1 h-[13.79px] mask-alpha mask-intersect mask-no-clip mask-no-repeat mask-position-[2.234px_4.335px] mask-size-[9.938px_5.085px] ml-0 mt-0 relative row-1 w-[14.407px]" style={{ maskImage: `url('${imgClipPath5}')` }} data-name="Clip-Path">
      <svg className="absolute block inset-0 size-full" fill="none" preserveAspectRatio="none" viewBox="0 0 14.407 13.7898">
        <g id="Clip-Path">
          <path d={svgPaths.p9d92200} fill="url(#paint0_linear_1_3601)" id="Layer" />
        </g>
        <defs>
          <linearGradient gradientUnits="userSpaceOnUse" id="paint0_linear_1_3601" x1="3.10949" x2="11.2763" y1="4.50476" y2="9.27599">
            <stop stopColor="#004786" />
            <stop offset="0.2" stopColor="#004786" />
            <stop offset="0.3" stopColor="#175490" />
            <stop offset="0.4" stopColor="#5076A9" />
            <stop offset="0.5" stopColor="#7289B7" />
            <stop offset="0.6" stopColor="#5B7CAD" />
            <stop offset="0.7" stopColor="#1A5691" />
            <stop offset="0.8" stopColor="#004786" />
            <stop offset="1" stopColor="#004786" />
          </linearGradient>
        </defs>
      </svg>
    </div>
  );
}

function Group7() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-[-2.23px] mt-[-4.33px] place-items-start relative row-1" data-name="Group">
      <ClipPath5 />
    </div>
  );
}

function ClipPathGroup5() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-0 mt-0 place-items-start relative row-1" data-name="Clip path group">
      <Group7 />
    </div>
  );
}

function Layer7() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-[0.02px] mt-[9.29px] place-items-start relative row-1" data-name="Layer">
      <ClipPathGroup5 />
    </div>
  );
}

function ClipPath6() {
  return (
    <div className="col-1 h-[6.101px] mask-alpha mask-intersect mask-no-clip mask-no-repeat mask-position-[1.097px_1.789px] mask-size-[4.081px_2.439px] ml-0 mt-0 relative row-1 w-[6.304px]" style={{ maskImage: `url('${imgClipPath6}')` }} data-name="Clip-Path">
      <svg className="absolute block inset-0 size-full" fill="none" preserveAspectRatio="none" viewBox="0 0 6.30446 6.10057">
        <g id="Clip-Path">
          <path d={svgPaths.p270ac500} fill="url(#paint0_linear_1_3598)" id="Layer" />
        </g>
        <defs>
          <linearGradient gradientUnits="userSpaceOnUse" id="paint0_linear_1_3598" x1="1.07877" x2="5.14697" y1="1.83733" y2="4.21668">
            <stop stopColor="#E7E8E9" />
            <stop offset="0.2" stopColor="#DDDEDF" />
            <stop offset="0.5" stopColor="#C2C3C5" />
            <stop offset="1" stopColor="#949698" />
          </linearGradient>
        </defs>
      </svg>
    </div>
  );
}

function Group8() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-[-1.1px] mt-[-1.79px] place-items-start relative row-1" data-name="Group">
      <ClipPath6 />
    </div>
  );
}

function ClipPathGroup6() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-0 mt-0 place-items-start relative row-1" data-name="Clip path group">
      <Group8 />
    </div>
  );
}

function Layer8() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-[7.27px] mt-[7.98px] place-items-start relative row-1" data-name="Layer">
      <ClipPathGroup6 />
    </div>
  );
}

function ClipPath7() {
  return (
    <div className="col-1 h-[13.793px] mask-alpha mask-intersect mask-no-clip mask-no-repeat mask-position-[2.232px_4.333px] mask-size-[9.945px_5.085px] ml-0 mt-0 relative row-1 w-[14.407px]" style={{ maskImage: `url('${imgClipPath7}')` }} data-name="Clip-Path">
      <svg className="absolute block inset-0 size-full" fill="none" preserveAspectRatio="none" viewBox="0 0 14.4068 13.7934">
        <g id="Clip-Path">
          <path d={svgPaths.p35fbc00} fill="url(#paint0_linear_1_3629)" id="Layer" />
        </g>
        <defs>
          <linearGradient gradientUnits="userSpaceOnUse" id="paint0_linear_1_3629" x1="3.10751" x2="11.2779" y1="4.50298" y2="9.2742">
            <stop stopColor="#004786" />
            <stop offset="0.2" stopColor="#004786" />
            <stop offset="0.3" stopColor="#175490" />
            <stop offset="0.4" stopColor="#5076A9" />
            <stop offset="0.5" stopColor="#7289B7" />
            <stop offset="0.6" stopColor="#5B7CAD" />
            <stop offset="0.7" stopColor="#1A5691" />
            <stop offset="0.8" stopColor="#004786" />
            <stop offset="1" stopColor="#004786" />
          </linearGradient>
        </defs>
      </svg>
    </div>
  );
}

function Group9() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-[-2.23px] mt-[-4.33px] place-items-start relative row-1" data-name="Group">
      <ClipPath7 />
    </div>
  );
}

function ClipPathGroup7() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-0 mt-0 place-items-start relative row-1" data-name="Clip path group">
      <Group9 />
    </div>
  );
}

function Layer9() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-[1.39px] mt-[6.96px] place-items-start relative row-1" data-name="Layer">
      <ClipPathGroup7 />
    </div>
  );
}

function ClipPath8() {
  return (
    <div className="col-1 h-[7.575px] mask-alpha mask-intersect mask-no-clip mask-no-repeat mask-position-[1.752px_1.777px] mask-size-[4.073px_4.017px] ml-0 mt-0 relative row-1 w-[7.584px]" style={{ maskImage: `url('${imgClipPath8}')` }} data-name="Clip-Path">
      <svg className="absolute block inset-0 size-full" fill="none" preserveAspectRatio="none" viewBox="0 0 7.58373 7.57472">
        <g id="Clip-Path">
          <path d={svgPaths.p18b52a00} fill="url(#paint0_linear_1_3590)" id="Layer" />
        </g>
        <defs>
          <linearGradient gradientUnits="userSpaceOnUse" id="paint0_linear_1_3590" x1="1.39917" x2="5.46916" y1="2.39192" y2="4.76591">
            <stop stopColor="#E7E8E9" />
            <stop offset="0.2" stopColor="#DDDEDF" />
            <stop offset="0.5" stopColor="#C2C3C5" />
            <stop offset="1" stopColor="#949698" />
          </linearGradient>
        </defs>
      </svg>
    </div>
  );
}

function Group10() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-[-1.75px] mt-[-1.78px] place-items-start relative row-1" data-name="Group">
      <ClipPath8 />
    </div>
  );
}

function ClipPathGroup8() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-0 mt-0 place-items-start relative row-1" data-name="Clip path group">
      <Group10 />
    </div>
  );
}

function Layer10() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-[4.51px] mt-[12.64px] place-items-start relative row-1" data-name="Layer">
      <ClipPathGroup8 />
    </div>
  );
}

function ClipPath9() {
  return (
    <div className="col-1 h-[6.101px] mask-alpha mask-intersect mask-no-clip mask-no-repeat mask-position-[1.1px_1.789px] mask-size-[4.079px_2.439px] ml-0 mt-0 relative row-1 w-[6.304px]" style={{ maskImage: `url('${imgClipPath9}')` }} data-name="Clip-Path">
      <svg className="absolute block inset-0 size-full" fill="none" preserveAspectRatio="none" viewBox="0 0 6.30447 6.10058">
        <g id="Clip-Path">
          <path d={svgPaths.p380ade00} fill="url(#paint0_linear_1_3581)" id="Layer" />
        </g>
        <defs>
          <linearGradient gradientUnits="userSpaceOnUse" id="paint0_linear_1_3581" x1="1.06986" x2="5.13807" y1="1.83555" y2="4.20954">
            <stop stopColor="#E7E8E9" />
            <stop offset="0.2" stopColor="#DDDEDF" />
            <stop offset="0.6" stopColor="#C2C3C5" />
            <stop offset="1" stopColor="#949698" />
          </linearGradient>
        </defs>
      </svg>
    </div>
  );
}

function Group12() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-[-1.1px] mt-[-1.79px] place-items-start relative row-1" data-name="Group">
      <ClipPath9 />
    </div>
  );
}

function ClipPathGroup9() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-0 mt-0 place-items-start relative row-1" data-name="Clip path group">
      <Group12 />
    </div>
  );
}

function Layer11() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-[5.89px] mt-[10.31px] place-items-start relative row-1" data-name="Layer">
      <ClipPathGroup9 />
    </div>
  );
}

function ClipPath10() {
  return (
    <div className="col-1 h-[7.593px] mask-alpha mask-intersect mask-no-clip mask-no-repeat mask-position-[1.769px_1.777px] mask-size-[4.07px_4.035px] ml-0 mt-0 relative row-1 w-[7.596px]" style={{ maskImage: `url('${imgClipPath10}')` }} data-name="Clip-Path">
      <svg className="absolute block inset-0 size-full" fill="none" preserveAspectRatio="none" viewBox="0 0 7.59618 7.59261">
        <g id="Clip-Path">
          <path d={svgPaths.pf9b1000} fill="url(#paint0_linear_1_3573)" id="Layer" />
        </g>
        <defs>
          <linearGradient gradientUnits="userSpaceOnUse" id="paint0_linear_1_3573" x1="2.12722" x2="6.19543" y1="2.82129" y2="5.19528">
            <stop stopColor="#949698" />
            <stop offset="0.2" stopColor="#9FA1A3" />
            <stop offset="0.6" stopColor="#BCBEBF" />
            <stop offset="1" stopColor="#E7E8E9" />
          </linearGradient>
        </defs>
      </svg>
    </div>
  );
}

function Group13() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-[-1.77px] mt-[-1.78px] place-items-start relative row-1" data-name="Group">
      <ClipPath10 />
    </div>
  );
}

function ClipPathGroup10() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-0 mt-0 place-items-start relative row-1" data-name="Clip path group">
      <Group13 />
    </div>
  );
}

function Layer12() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-[4.14px] mt-[2.33px] place-items-start relative row-1" data-name="Layer">
      <ClipPathGroup10 />
    </div>
  );
}

function Group1() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-[25.75px] mt-0 place-items-start relative row-1" data-name="Group">
      <Layer2 />
      <Layer3 />
      <Layer4 />
      <Layer5 />
      <Layer6 />
      <Layer7 />
      <Layer8 />
      <Layer9 />
      <Layer10 />
      <Layer11 />
      <Layer12 />
    </div>
  );
}

function Layer() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-0 mt-0 place-items-start relative row-1" data-name="Layer">
      <Layer1 />
      <Group1 />
    </div>
  );
}

function Group() {
  return (
    <div className="col-1 grid-cols-[max-content] grid-rows-[max-content] inline-grid ml-0 mt-0 place-items-start relative row-1" data-name="Group">
      <div className="col-1 h-[15.439px] ml-[84.81px] mt-[12.56px] relative row-1 w-[23.422px]" data-name="Vector">
        <svg className="absolute block inset-0 size-full" fill="none" preserveAspectRatio="none" viewBox="0 0 23.4216 15.4393">
          <path d={svgPaths.p5795100} fill="var(--fill-0, #03B585)" id="Vector" />
        </svg>
      </div>
      <Layer />
    </div>
  );
}

function Group11() {
  return (
    <div className="grid-cols-[max-content] grid-rows-[max-content] inline-grid leading-[0] place-items-start relative shrink-0">
      <Group />
      <div className="col-1 h-[15.437px] ml-[74.32px] mt-[12.56px] relative row-1 w-[0.358px]" data-name="Vector">
        <svg className="absolute block inset-0 size-full" fill="none" preserveAspectRatio="none" viewBox="0 0 0.3578 15.4375">
          <path d={svgPaths.p3043ed00} fill="var(--fill-0, #9FA1A4)" id="Vector" />
        </svg>
      </div>
    </div>
  );
}

function Logo() {
  return (
    <div className="h-full relative shrink-0" data-name="Logo">
      <div className="flex flex-col items-center size-full">
        <div className="content-stretch flex flex-col items-center pl-[32px] pr-[16px] pt-[4px] relative size-full">
          <Group11 />
        </div>
      </div>
    </div>
  );
}

function LinkText() {
  return (
    <div className="content-stretch flex items-center pr-[28px] relative shrink-0" data-name="Link text">
      <p className="font-['Founders_Grotesk:Regular',sans-serif] leading-[18px] mr-[-28px] not-italic relative shrink-0 text-[#008053] text-[14px] tracking-[0.16px] whitespace-nowrap">Products</p>
    </div>
  );
}

function IconWrapper() {
  return (
    <div className="content-stretch flex items-center relative shrink-0 w-[20px]" data-name="Icon wrapper">
      <div className="overflow-clip relative shrink-0 size-[20px]" data-name="Chevron--down">
        <div aria-hidden="true" className="absolute bg-[rgba(255,255,255,0)] inset-0 mix-blend-multiply pointer-events-none" />
        <div className="absolute inset-[33.13%_18.75%_31.25%_18.75%]" data-name="Vector">
          <svg className="absolute block inset-0 size-full" fill="none" preserveAspectRatio="none" viewBox="0 0 12.5 7.125">
            <path d={svgPaths.p23048b80} fill="var(--fill-0, #008053)" id="Vector" />
          </svg>
        </div>
      </div>
    </div>
  );
}

function LinkText1() {
  return (
    <div className="content-stretch flex items-center pr-[28px] relative shrink-0" data-name="Link text">
      <p className="font-['Founders_Grotesk:Regular',sans-serif] leading-[18px] mr-[-28px] not-italic relative shrink-0 text-[#008053] text-[14px] tracking-[0.16px] whitespace-nowrap">Solutions</p>
    </div>
  );
}

function IconWrapper1() {
  return (
    <div className="content-stretch flex items-center relative shrink-0 w-[20px]" data-name="Icon wrapper">
      <div className="overflow-clip relative shrink-0 size-[20px]" data-name="Chevron--down">
        <div aria-hidden="true" className="absolute bg-[rgba(255,255,255,0)] inset-0 mix-blend-multiply pointer-events-none" />
        <div className="absolute inset-[33.13%_18.75%_31.25%_18.75%]" data-name="Vector">
          <svg className="absolute block inset-0 size-full" fill="none" preserveAspectRatio="none" viewBox="0 0 12.5 7.125">
            <path d={svgPaths.p23048b80} fill="var(--fill-0, #008053)" id="Vector" />
          </svg>
        </div>
      </div>
    </div>
  );
}

function LinkText2() {
  return (
    <div className="content-stretch flex items-center pr-[28px] relative shrink-0" data-name="Link text">
      <p className="font-['Founders_Grotesk:Regular',sans-serif] leading-[18px] mr-[-28px] not-italic relative shrink-0 text-[#008053] text-[14px] tracking-[0.16px] whitespace-nowrap">Support</p>
    </div>
  );
}

function IconWrapper2() {
  return (
    <div className="content-stretch flex items-center relative shrink-0 w-[20px]" data-name="Icon wrapper">
      <div className="overflow-clip relative shrink-0 size-[20px]" data-name="Chevron--down">
        <div aria-hidden="true" className="absolute bg-[rgba(255,255,255,0)] inset-0 mix-blend-multiply pointer-events-none" />
        <div className="absolute inset-[33.13%_18.75%_31.25%_18.75%]" data-name="Vector">
          <svg className="absolute block inset-0 size-full" fill="none" preserveAspectRatio="none" viewBox="0 0 12.5 7.125">
            <path d={svgPaths.p23048b80} fill="var(--fill-0, #008053)" id="Vector" />
          </svg>
        </div>
      </div>
    </div>
  );
}

function LinkText3() {
  return (
    <div className="content-stretch flex items-center pr-[28px] relative shrink-0" data-name="Link text">
      <p className="font-['Founders_Grotesk:Regular',sans-serif] leading-[18px] mr-[-28px] not-italic relative shrink-0 text-[#008053] text-[14px] tracking-[0.16px] whitespace-nowrap">Partners</p>
    </div>
  );
}

function IconWrapper3() {
  return (
    <div className="content-stretch flex items-center relative shrink-0 w-[20px]" data-name="Icon wrapper">
      <div className="overflow-clip relative shrink-0 size-[20px]" data-name="Chevron--down">
        <div aria-hidden="true" className="absolute bg-[rgba(255,255,255,0)] inset-0 mix-blend-multiply pointer-events-none" />
        <div className="absolute inset-[33.13%_18.75%_31.25%_18.75%]" data-name="Vector">
          <svg className="absolute block inset-0 size-full" fill="none" preserveAspectRatio="none" viewBox="0 0 12.5 7.125">
            <path d={svgPaths.p23048b80} fill="var(--fill-0, #008053)" id="Vector" />
          </svg>
        </div>
      </div>
    </div>
  );
}

function LinkText4() {
  return (
    <div className="content-stretch flex items-center pr-[28px] relative shrink-0" data-name="Link text">
      <p className="font-['Founders_Grotesk:Regular',sans-serif] leading-[18px] mr-[-28px] not-italic relative shrink-0 text-[#008053] text-[14px] tracking-[0.16px] whitespace-nowrap">Community</p>
    </div>
  );
}

function IconWrapper4() {
  return (
    <div className="content-stretch flex items-center relative shrink-0 w-[20px]" data-name="Icon wrapper">
      <div className="overflow-clip relative shrink-0 size-[20px]" data-name="Chevron--down">
        <div aria-hidden="true" className="absolute bg-[rgba(255,255,255,0)] inset-0 mix-blend-multiply pointer-events-none" />
        <div className="absolute inset-[33.13%_18.75%_31.25%_18.75%]" data-name="Vector">
          <svg className="absolute block inset-0 size-full" fill="none" preserveAspectRatio="none" viewBox="0 0 12.5 7.125">
            <path d={svgPaths.p23048b80} fill="var(--fill-0, #008053)" id="Vector" />
          </svg>
        </div>
      </div>
    </div>
  );
}

function LinkText5() {
  return (
    <div className="content-stretch flex items-center pr-[28px] relative shrink-0" data-name="Link text">
      <p className="font-['Founders_Grotesk:Regular',sans-serif] leading-[18px] mr-[-28px] not-italic relative shrink-0 text-[#008053] text-[14px] tracking-[0.16px] whitespace-nowrap">Events</p>
    </div>
  );
}

function IconWrapper5() {
  return (
    <div className="content-stretch flex items-center relative shrink-0 w-[20px]" data-name="Icon wrapper">
      <div className="overflow-clip relative shrink-0 size-[20px]" data-name="Chevron--down">
        <div aria-hidden="true" className="absolute bg-[rgba(255,255,255,0)] inset-0 mix-blend-multiply pointer-events-none" />
      </div>
    </div>
  );
}

function LeftMenuItems() {
  return (
    <div className="content-stretch flex h-full items-center relative shrink-0" data-name="Left menu Items">
      <div className="content-stretch flex flex-col h-[48px] items-center justify-center px-[16px] relative shrink-0 w-[112px]" data-name="navigation-item">
        <div className="content-stretch flex gap-[8px] items-center relative shrink-0 w-full" data-name="Link">
          <div aria-hidden="true" className="absolute bg-[rgba(255,255,255,0)] inset-0 mix-blend-multiply pointer-events-none" />
          <LinkText />
          <IconWrapper />
        </div>
      </div>
      <div className="content-stretch flex flex-col h-[48px] items-center justify-center px-[16px] relative shrink-0 w-[113px]" data-name="navigation-item">
        <div className="content-stretch flex gap-[8px] items-center relative shrink-0 w-full" data-name="Link">
          <div aria-hidden="true" className="absolute bg-[rgba(255,255,255,0)] inset-0 mix-blend-multiply pointer-events-none" />
          <LinkText1 />
          <IconWrapper1 />
        </div>
      </div>
      <div className="content-stretch flex flex-col h-[48px] items-center justify-center px-[16px] relative shrink-0 w-[107px]" data-name="navigation-item">
        <div className="content-stretch flex gap-[8px] items-center relative shrink-0 w-full" data-name="Link">
          <div aria-hidden="true" className="absolute bg-[rgba(255,255,255,0)] inset-0 mix-blend-multiply pointer-events-none" />
          <LinkText2 />
          <IconWrapper2 />
        </div>
      </div>
      <div className="content-stretch flex flex-col h-[48px] items-center justify-center px-[16px] relative shrink-0 w-[110px]" data-name="navigation-item">
        <div className="content-stretch flex gap-[8px] items-center relative shrink-0 w-full" data-name="Link">
          <div aria-hidden="true" className="absolute bg-[rgba(255,255,255,0)] inset-0 mix-blend-multiply pointer-events-none" />
          <LinkText3 />
          <IconWrapper3 />
        </div>
      </div>
      <div className="content-stretch flex flex-col h-[48px] items-center justify-center px-[16px] relative shrink-0 w-[127px]" data-name="navigation-item">
        <div className="content-stretch flex gap-[8px] items-center relative shrink-0 w-full" data-name="Link">
          <div aria-hidden="true" className="absolute bg-[rgba(255,255,255,0)] inset-0 mix-blend-multiply pointer-events-none" />
          <LinkText4 />
          <IconWrapper4 />
        </div>
      </div>
      <div className="content-stretch flex flex-col h-[48px] items-center justify-center px-[16px] relative shrink-0 w-[99px]" data-name="navigation-item">
        <div className="content-stretch flex gap-[8px] items-center relative shrink-0 w-full" data-name="Link">
          <div aria-hidden="true" className="absolute bg-[rgba(255,255,255,0)] inset-0 mix-blend-multiply pointer-events-none" />
          <LinkText5 />
          <IconWrapper5 />
        </div>
      </div>
    </div>
  );
}

function LeftIconSet() {
  return (
    <div className="content-stretch flex h-[48px] items-center relative shrink-0" data-name="Left Icon set">
      <Logo />
      <LeftMenuItems />
    </div>
  );
}

function SearchIcon() {
  return (
    <div className="content-stretch flex items-center justify-center p-[16px] relative shrink-0" data-name="Search icon">
      <div className="overflow-clip relative shrink-0 size-[16px]" data-name="Search">
        <div aria-hidden="true" className="absolute bg-[rgba(255,255,255,0)] inset-0 mix-blend-multiply pointer-events-none" />
        <div className="absolute inset-[6.14%_9.37%_9.37%_6.14%]" data-name="Vector">
          <svg className="absolute block inset-0 size-full" fill="none" preserveAspectRatio="none" viewBox="0 0 13.5177 13.5177">
            <path d={svgPaths.p23d74400} fill="var(--fill-0, #008053)" id="Vector" />
          </svg>
        </div>
      </div>
    </div>
  );
}

function LinkText6() {
  return (
    <div className="content-stretch flex items-center pr-[28px] relative shrink-0" data-name="Link text">
      <p className="font-['Founders_Grotesk:Regular',sans-serif] leading-[18px] mr-[-28px] not-italic relative shrink-0 text-[#008053] text-[14px] tracking-[0.16px] whitespace-nowrap">Contact us</p>
    </div>
  );
}

function ContactUs() {
  return (
    <div className="h-full relative shrink-0 w-[95px]" data-name="Contact Us">
      <div className="flex flex-col items-center justify-center size-full">
        <div className="content-stretch flex flex-col items-center justify-center px-[16px] relative size-full">
          <div className="content-stretch flex gap-[8px] items-center relative shrink-0 w-full" data-name="Link">
            <div aria-hidden="true" className="absolute bg-[rgba(255,255,255,0)] inset-0 mix-blend-multiply pointer-events-none" />
            <LinkText6 />
          </div>
        </div>
      </div>
    </div>
  );
}

function Icon() {
  return (
    <div className="content-stretch flex flex-col items-start overflow-clip relative shrink-0 z-[1]" data-name="Icon">
      <div className="content-stretch flex flex-col items-start py-[3px] relative shrink-0 w-[16px]" data-name="Flag">
        <div aria-hidden="true" className="absolute bg-[rgba(255,255,255,0)] inset-0 mix-blend-multiply pointer-events-none" />
        <div className="h-[10px] relative shrink-0 w-full" data-name="image 3">
          <img alt="" className="absolute inset-0 max-w-none object-cover pointer-events-none size-full" src={imgImage3} />
        </div>
      </div>
    </div>
  );
}

function ButtonContent() {
  return (
    <div className="h-[48px] relative rounded-[8px] shrink-0 w-full" data-name="Button content">
      <div className="flex flex-row items-center overflow-clip rounded-[inherit] size-full">
        <div className="content-stretch flex isolate items-center p-[16px] relative size-full">
          <Icon />
        </div>
      </div>
    </div>
  );
}

function Icon1() {
  return (
    <div className="content-stretch flex flex-col items-start overflow-clip relative shrink-0 z-[1]" data-name="Icon">
      <div className="overflow-clip relative shrink-0 size-[16px]" data-name="User--avatar">
        <div aria-hidden="true" className="absolute bg-[rgba(255,255,255,0)] inset-0 mix-blend-multiply pointer-events-none" />
        <div className="absolute inset-[6.25%]" data-name="Vector">
          <svg className="absolute block inset-0 size-full" fill="none" preserveAspectRatio="none" viewBox="0 0 14 14">
            <g id="Vector">
              <path d={svgPaths.pa486630} fill="#008053" />
              <path d={svgPaths.p2b8c7200} fill="#008053" />
            </g>
          </svg>
        </div>
      </div>
    </div>
  );
}

function ButtonContent1() {
  return (
    <div className="relative rounded-[8px] shrink-0 w-full" data-name="Button content">
      <div className="flex flex-row items-center overflow-clip rounded-[inherit] size-full">
        <div className="content-stretch flex isolate items-center p-[16px] relative size-full">
          <Icon1 />
        </div>
      </div>
    </div>
  );
}

function Icon2() {
  return (
    <div className="content-stretch flex flex-col items-start overflow-clip relative shrink-0 z-[1]" data-name="Icon">
      <div className="overflow-clip relative shrink-0 size-[16px]" data-name="Shopping--cart">
        <div aria-hidden="true" className="absolute bg-[rgba(255,255,255,0)] inset-0 mix-blend-multiply pointer-events-none" />
        <div className="absolute inset-[6.25%_9.3%_6.25%_0]" data-name="Vector">
          <svg className="absolute block inset-0 size-full" fill="none" preserveAspectRatio="none" viewBox="0 0 14.5123 14.0001">
            <g id="Vector">
              <path d={svgPaths.p8533df0} fill="#008053" />
              <path d={svgPaths.p15cba880} fill="#008053" />
              <path d={svgPaths.p1f020100} fill="#008053" />
            </g>
          </svg>
        </div>
      </div>
    </div>
  );
}

function ButtonContent2() {
  return (
    <div className="relative rounded-[8px] shrink-0 w-full" data-name="Button content">
      <div className="flex flex-row items-center overflow-clip rounded-[inherit] size-full">
        <div className="content-stretch flex isolate items-center p-[16px] relative size-full">
          <Icon2 />
        </div>
      </div>
    </div>
  );
}

function RightMenuItems() {
  return (
    <div className="content-stretch flex h-[48px] items-center px-[32px] relative shrink-0" data-name="Right Menu Items">
      <div className="h-full relative shrink-0" data-name="Search - Default">
        <div aria-hidden="true" className="absolute bg-[rgba(255,255,255,0)] inset-0 mix-blend-multiply pointer-events-none" />
        <div className="flex flex-row items-center size-full">
          <div className="content-stretch flex items-center relative size-full">
            <SearchIcon />
          </div>
        </div>
      </div>
      <ContactUs />
      <div className="h-full relative rounded-[8px] shrink-0 w-[48px]" data-name="Country Selector">
        <div aria-hidden="true" className="absolute bg-[rgba(255,255,255,0)] inset-0 mix-blend-multiply pointer-events-none rounded-[8px]" />
        <div className="flex flex-col items-center justify-center overflow-clip rounded-[inherit] size-full">
          <div className="content-stretch flex flex-col items-center justify-center relative size-full">
            <ButtonContent />
          </div>
        </div>
      </div>
      <div className="h-full relative rounded-[8px] shrink-0 w-[48px]" data-name="My Account">
        <div aria-hidden="true" className="absolute bg-[rgba(255,255,255,0)] inset-0 mix-blend-multiply pointer-events-none rounded-[8px]" />
        <div className="flex flex-col justify-center overflow-clip rounded-[inherit] size-full">
          <div className="content-stretch flex flex-col items-start justify-center relative size-full">
            <ButtonContent1 />
          </div>
        </div>
      </div>
      <div className="h-full relative rounded-[8px] shrink-0 w-[48px]" data-name="Cart">
        <div aria-hidden="true" className="absolute bg-[rgba(255,255,255,0)] inset-0 mix-blend-multiply pointer-events-none rounded-[8px]" />
        <div className="flex flex-col items-center justify-center overflow-clip rounded-[inherit] size-full">
          <div className="content-stretch flex flex-col items-center justify-center relative size-full">
            <ButtonContent2 />
          </div>
        </div>
      </div>
    </div>
  );
}

export default function UseThisCopilot() {
  return (
    <div className="bg-white relative size-full" data-name="USE THIS COPILOT 1">
      <div className="absolute bg-white content-stretch flex items-center justify-between left-0 top-0 w-[1440px]" data-name="Header">
        <div aria-hidden="true" className="absolute border-[#e0e0e0] border-b border-solid inset-0 pointer-events-none" />
        <LeftIconSet />
        <div className="bg-[rgba(255,255,255,0)] flex-[1_0_0] h-[48px] min-w-px" data-name="Spacer" />
        <RightMenuItems />
      </div>
    </div>
  );
}
```

**Continue to Part 2 for Footer Component...**

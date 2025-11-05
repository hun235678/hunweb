# hunweb

import React from "react";
import x12 from "./1-2.png";
import { Div } from "./Div";
import { DivWrapper } from "./DivWrapper";
import { Frame } from "./Frame";
import { FrameWrapper } from "./FrameWrapper";
import { SectionComponentNode } from "./SectionComponentNode";
import line9 from "./line-9.svg";

export const Screen = () => {
  return (
    <div className="bg-[#fffffd] overflow-hidden w-full min-w-[1920px] min-h-[8919px] relative">
      <Frame />
      <div className="absolute top-[1848px] left-px w-[1920px] h-[1080px] bg-[#d6d6d6] overflow-hidden">
        <img
          className="absolute top-0 left-0 w-[1932px] h-[1083px] aspect-[1.78] object-cover"
          alt="Element"
          src={x12}
        />

        <div className="absolute left-[calc(50.00%_-_248px)] bottom-[50px] w-[496px] text-white text-[40px] text-center tracking-[-1.20px] leading-[60px] [font-family:'Baskervville-Regular',Helvetica] font-normal">
          Sauce Salon
        </div>

        <div className="absolute top-[1080px] left-0 w-[1920px] h-[600px] flex overflow-hidden">
          <div className="mt-[5px] w-[1920px] h-[600px]" />
        </div>
      </div>

      <FrameWrapper />
      <div className="flex flex-col w-[385px] items-start gap-5 absolute top-[1040px] left-60">
        <div className="relative self-stretch mt-[-1.00px] [font-family:'Pretendard_Variable-Medium',Helvetica] font-medium text-[#1e1e1e] text-[32px] tracking-[-0.80px] leading-[48px]">
          일상의 흔적에 감각을 입히다
        </div>

        <div className="flex flex-col w-[385px] h-[458px] items-start gap-10 relative">
          <p className="relative self-stretch mt-[-1.00px] [font-family:'Pretendard_Variable-Regular',Helvetica] font-normal text-[#717171] text-[19px] tracking-[-0.47px] leading-[28.5px]">
            당신의 일상에서 만날 수 있는 흔적들을 라이프스타일에 그대로
            드러내세요. Sauce Salon은 당신의 일상 속 기억을 예상하지 못한
            얼룩으로 드러내고자 합니다.
          </p>

          <div className="inline-flex flex-col items-start gap-4 relative flex-[0_0_auto]">
            <div className="relative self-stretch mt-[-1.00px] [font-family:'Pretendard_Variable-Regular',Helvetica] font-normal text-[#333231] text-lg tracking-[-0.45px] leading-[27px]">
              김치찌개
            </div>

            <div className="relative self-stretch [font-family:'Pretendard_Variable-Regular',Helvetica] font-normal text-[#9d9c9a] text-lg tracking-[-0.45px] leading-[27px]">
              마라탕
            </div>

            <div className="relative self-stretch [font-family:'Pretendard_Variable-Regular',Helvetica] font-normal text-[#9d9c9a] text-lg tracking-[-0.45px] leading-[27px]">
              국밥
            </div>

            <div className="relative self-stretch [font-family:'Pretendard_Variable-Regular',Helvetica] font-normal text-[#9d9c9a] text-lg tracking-[-0.45px] leading-[27px]">
              라면
            </div>

            <div className="relative self-stretch [font-family:'Pretendard_Variable-Regular',Helvetica] font-normal text-[#9d9c9a] text-lg tracking-[-0.45px] leading-[27px]">
              학식
            </div>

            <div className="relative self-stretch [font-family:'Pretendard_Variable-Regular',Helvetica] font-normal text-[#9d9c9a] text-lg tracking-[-0.45px] leading-[27px]">
              기타
            </div>
          </div>
        </div>
      </div>

      <img
        className="absolute top-[1479px] left-60 w-[61px] h-px object-cover"
        alt="Line"
        src={line9}
      />

      <DivWrapper />
      <Div />
      <SectionComponentNode />
    </div>
  );
};

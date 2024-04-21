<script setup>
import EventDetail from "./EventDetail.vue";
import EventCalendar from "./EventCalendar.vue";
import SectionHeader from "./SectionHeader.vue";
</script>

<template>
  <div class="flex flex-col items-center justify-center py-16 md:py-24">
    <SectionHeader title="Sự kiện cưới">
      ...tình yêu không phải là nhìn chằm chằm vào nhau, mà là nhìn chằm chằm về
      cùng một hướng...
    </SectionHeader>
    <div class="flex flex-col gap-4 md:flex-row md:justify-center">
      <EventDetail
        address="Trung tâm tiệc cưới Crown Place, Số 19 phố Bùi Sính, tt Tiền Hải, Thái Bình"
        class="order-0 md:order-first md:basis-[20%]"
        img-src="/banhcay.jpg"
        maps-url="https://www.google.com/maps/place/Crown+Restaurant/@20.4043481,106.4988413,18z/data=!3m1!4b1!4m6!3m5!1s0x3135f90add53e5c1:0x210cdc104411d717!8m2!3d20.4043456!4d106.5001288!16s%2Fg%2F11fk4pcvkx?entry=ttu"
        time="10:30 01/05/2024"
        title="TIỆC CƯỚI NHÀ CHÚ RỂ"
      />
      <EventCalendar class="md:order-0 order-first basis-[60%]" />
      <EventDetail
        address="Đồng Mái, Phù Ủng, Ân Thi, Hưng Yên"
        class="md:basis-[20%]"
        img-src="/hungyen.jpg"
        maps-url="https://www.google.com/maps/place/Th%C3%B4n+la+m%C3%A1t/@20.8681073,106.1227785,16z/data=!4m14!1m7!3m6!1s0x3135bd30c781fbb3:0x66c7b4e36c3019cd!2zQ2jDuWEgUGjDumMgTMOibSAoTGEgTcOhdCk!8m2!3d20.8781917!4d106.127779!16s%2Fg%2F11f4ldmwh_!3m5!1s0x3135bd13e7d3066b:0x51ad59b56ba3a7a7!8m2!3d20.8687569!4d106.1260381!16s%2Fg%2F11sd6x13hz?entry=ttu"
        time="16:30 01/05/2024"
        title="TIỆC CƯỚI NHÀ CÔ DÂU"
      />
    </div>
  </div>
</template>

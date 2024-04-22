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
        address="Trung tâm tiệc cưới Crown Palace, số 19 Bùi Sính, Tiền Hải, Thái Bình"
        class="order-0 md:order-first md:basis-[20%]"
        img-src="/thaibinh.png"
        maps-url="https://www.google.com/maps/place/Crown+Restaurant/@20.4033144,106.4990967,18.04z/data=!4m10!1m2!2m1!1zQ3Jvd24gUGFsYWNlIHRp4buBbiBo4bqjaQ!3m6!1s0x3135f90add53e5c1:0x210cdc104411d717!8m2!3d20.4043456!4d106.5001288!15sChlDcm93biBQYWxhY2UgdGnhu4FuIGjhuqNpWhsiGWNyb3duIHBhbGFjZSB0aeG7gW4gaOG6o2mSAQpyZXN0YXVyYW50mgEjQ2haRFNVaE5NRzluUzBWSlEwRm5TVVJ6ZVdJdGNWVjNFQUXgAQA!16s%2Fg%2F11fk4pcvkx?entry=ttu"
        time="10:30 01/05/2024"
        title="TIỆC CƯỚI NHÀ CHÚ RỂ"
      />
      <EventCalendar class="md:order-0 order-first basis-[60%]" />
      <EventDetail
        address="Đồng Mái, Phù Ủng, Ân Thi, Hưng Yên"
        class="md:basis-[20%]"
        img-src="/hungyen.jpg"
        maps-url="https://www.google.com/maps/place/Th%C3%B4n+%C4%90%E1%BB%93ng+M%C3%A1i,+Ph%C3%B9+%E1%BB%A6ng,+%C3%82n+Thi,+H%C6%B0ng+y%C3%AAn/@20.8715755,106.1143427,17z/data=!3m1!4b1!4m6!3m5!1s0x3135bd20cf060def:0x8bc98f14ac1eeba3!8m2!3d20.8715755!4d106.1169176!16s%2Fg%2F11hd6ztsc4?entry=ttu"
        time="16:30 01/05/2024"
        title="TIỆC CƯỚI NHÀ CÔ DÂU"
      />
    </div>
  </div>
</template>

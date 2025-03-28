<script>
    import ClassLevel from './ClassLevel.svelte';
  
    const classes = [
      {
        level: 1,
        title: "Foundational Flow",
        description: "Learn to speak, understand, read, and write Spanish for basic day to day interactions.",
        classes: [
          {
            startDate: "April 1, 2025",
            day: "Tuesday",
            timeCST: "8:00 AM",
            spots: 8,
            totalSpots: 8,
            price: 197,
            originalPrice: 297,
            link: "https://api.leadconnectorhq.com/widget/booking/1zvwg1E3nB0GX5g8Q30q"
          },
          {
            startDate: "April 1, 2025",
            day: "Tuesday",
            timeCST: "9:15 AM",
            spots: 8,
            totalSpots: 8,
            price: 197,
            originalPrice: 297,
            link: "https://api.leadconnectorhq.com/widget/bookings/ff-1-915am"
          },
          {
            startDate: "April 1, 2025",
            day: "Tuesday",
            timeCST: "10:30 AM",
            spots: 0,
            totalSpots: 8,
            price: 197,
            originalPrice: 297,
            link: ""
          },
          {
            startDate: "April 2, 2025",
            day: "Wednesday",
            timeCST: "8:00 AM",
            spots: 0,
            totalSpots: 8,
            price: 197,
            originalPrice: 297,
            link: ""
          },
          {
            startDate: "April 2, 2025",
            day: "Wednesday",
            timeCST: "9:15 AM",
            spots: 7,
            totalSpots: 8,
            price: 197,
            originalPrice: 297,
            link: "https://api.leadconnectorhq.com/widget/booking/ijer6JJYJhkJUtXCF6zK"
          },
          {
            startDate: "April 3, 2025",
            day: "Thursday",
            timeCST: "9:15 AM",
            spots: 5,
            totalSpots: 8,
            price: 197,
            originalPrice: 297,
            link: "https://api.leadconnectorhq.com/widget/booking/oUsXihMKr1ymQANw1eyA"
          }
        ]
      },
      {
  "level": 2,
  "title": "Conversational Flow",
  "description": "Go deeper and gain fluency in natural, spontaneous conversations in Spanish",
  "classes": [
    {
      "startDate": "April 3, 2025",
      "day": "Thursday",
      "timeCST": "9:00 AM",
      "spots": 5,
      "totalSpots": 8,
      "price": 197,
      "originalPrice": 297,
      "link": "https://api.leadconnectorhq.com/widget/booking/NiWojInPUMLWIomXZHqY"
    },
    {
      "startDate": "April 3, 2025",
      "day": "Thursday",
      "timeCST": "11:30 AM",
      "spots": 0,
      "totalSpots": 8,
      "price": 197,
      "originalPrice": 297,
      "link": "https://buy.stripe.com/placeholder2"
    },
    {
      "startDate": "April 1, 2025",
      "day": "Tuesday",
      "timeCST": "2:00 PM",
      "spots": 0,
      "totalSpots": 8,
      "price": 197,
      "originalPrice": 297,
      "link": "https://buy.stripe.com/placeholder3"
    },
    {
      "startDate": "April 2, 2025",
      "day": "Wednesday",
      "timeCST": "2:00 PM",
      "spots": 0,
      "totalSpots": 8,
      "price": 197,
      "originalPrice": 297,
      "link": "https://buy.stripe.com/placeholder4"
    },
    {
      "startDate": "April 3, 2025",
      "day": "Thursday",
      "timeCST": "2:00 PM",
      "spots": 0,
      "totalSpots": 8,
      "price": 197,
      "originalPrice": 297,
      "link": "https://buy.stripe.com/placeholder5"
    },
    {
      "startDate": "April 1, 2025",
      "day": "Tuesday",
      "timeCST": "3:15 PM",
      "spots": 0,
      "totalSpots": 8,
      "price": 197,
      "originalPrice": 297,
      "link": "https://buy.stripe.com/placeholder6"
    }
  ]
},
{
  "level": 3,
  "title": "360 Flow",
  "description": "Advanced fluency and comprehensive understanding in Spanish",
  "classes": [
    {
      "startDate": "April 2, 2025",
      "day": "Wednesday",
      "timeCST": "11:30 AM",
      "spots": 2,
      "totalSpots": 8,
      "price": 197,
      "originalPrice": 297,
      "link": "https://api.leadconnectorhq.com/widget/booking/9UhVN62mdZxJH8OzJVp7"
    },
    {
      "startDate": "April 2, 2025",
      "day": "Wednesday",
      "timeCST": "3:15 PM",
      "spots": 0,
      "totalSpots": 8,
      "price": 197,
      "originalPrice": 297,
      "link": "https://buy.stripe.com/placeholder8"
    },
    {
      "startDate": "April 3, 2025",
      "day": "Thursday",
      "timeCST": "3:15 PM",
      "spots": 0,
      "totalSpots": 8,
      "price": 197,
      "originalPrice": 297,
      "link": "https://buy.stripe.com/placeholder9"
    },
    {
      "startDate": "April 1, 2025",
      "day": "Tuesday",
      "timeCST": "4:30 PM",
      "spots": 0,
      "totalSpots": 8,
      "price": 197,
      "originalPrice": 297,
      "link": "https://buy.stripe.com/placeholder10"
    },
    {
      "startDate": "April 2, 2025",
      "day": "Wednesday",
      "timeCST": "4:30 PM",
      "spots": 0,
      "totalSpots": 8,
      "price": 197,
      "originalPrice": 297,
      "link": "https://buy.stripe.com/placeholder11"
    },
    {
      "startDate": "April 3, 2025",
      "day": "Thursday",
      "timeCST": "4:30 PM",
      "spots": 0,
      "totalSpots": 8,
      "price": 197,
      "originalPrice": 297,
      
      "link": "https://buy.stripe.com/placeholder12"
    }
  ]
}
    ];
  </script>
  
  <section class="">
    {#each classes as level}
      <ClassLevel level={level} sectionClass={`level${level.level}-section`} />
    {/each}
  </section>
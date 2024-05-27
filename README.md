<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>School Notice Board</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        .notice-board {
            width: 60%;
            margin: 50px auto;
            padding: 20px;
            background-color: #ffffff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }

        .notice-board h1 {
            text-align: center;
            color: #333333;
            margin-bottom: 20px;
        }

        .notice {
            border-bottom: 1px solid #dddddd;
            padding: 10px 0;
        }

        .notice h2 {
            color: #ff5722;
            margin: 0;
        }

        .notice p {
            color: #555555;
            margin: 5px 0;
        }

        .notice .date {
            font-size: 0.9em;
            color: #888888;
        }
    </style>
</head>
<body>
    <div class="notice-board">
        <h1>স্কুল নোটিশ বোর্ড</h1>
        <div class="notice">
            <h2>নোটিশ ১</h2>
            <p>এই সপ্তাহের ক্লাস রুটিন পরিবর্তন হয়েছে। বিস্তারিত জানার জন্য অফিসে যোগাযোগ করুন।</p>
            <p class="date">তারিখ: ২৫ মে ২০২৪</p>
        </div>
        <div class="notice">
            <h2>নোটিশ ২</h2>
            <p>আগামীকাল স্কুলে প্যারেন্ট-টিচার মিটিং অনুষ্ঠিত হবে। সকলে উপস্থিত থাকার জন্য অনুরোধ করা হলো।</p>
            <p class="date">তারিখ: ২৬ মে ২০২৪</p>
        </div>
        <!-- আরো নোটিশ এখানে যুক্ত করুন -->
    </div>
</body>
</html>









<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>School Notice Board</title>
    <style>
        /* CSS এর কোড */
    </style>
</head>
<body>
    <div class="notice-board">
        <h1>স্কুল নোটিশ বোর্ড</h1>
        <div id="notices-container">
            <!-- নোটিশ গুলি এখানে ডায়নামিক ভাবে যুক্ত হবে -->
        </div>
    </div>

    <script>
        // JavaScript এর কোড
        // ধরি, নোটিশ গুলির তথ্য একটি অ্যারেতে আছে
        const notices = [
            { title: "নোটিশ ১", content: "এই সপ্তাহের ক্লাস রুটিন পরিবর্তন হয়েছে। বিস্তারিত জানার জন্য অফিসে যোগাযোগ করুন।", date: "তারিখ: ২৫ মে ২০২৪" },
            { title: "নোটিশ ২", content: "আগামীকাল স্কুলে প্যারেন্ট-টিচার মিটিং অনুষ্ঠিত হবে। সকলে উপস্থিত থাকার জন্য অনুরোধ করা হলো।", date: "তারিখ: ২৬ মে ২০২৪" }
            // আরও নোটিশ এখানে যোগ করা যেতে পারে
        ];

        // নোটিশ গুলির তথ্য ব্যবহার করে HTML তৈরি করা
        const noticesContainer = document.getElementById("notices-container");
        notices.forEach(notice => {
            const noticeElement = document.createElement("div");
            noticeElement.classList.add("notice");
            noticeElement.innerHTML = `
                <h2>${notice.title}</h2>
                <p>${notice.content}</p>
                <p class="date">${notice.date}</p>
            `;
            noticesContainer.appendChild(noticeElement);
        });
    </script>
</body>
</html>







এই উদাহরণে, আমরা JavaScript ব্যবহার করে নোটিশ বোর্ডে নতুন নোটিশ গুলি ডায়নামিকভাবে যোগ করেছি। প্রতিটি নোটিশের বিস্তারিত তথ্য একটি অ্যারে থেকে নেওয়া হয়েছে এবং একটি HTML এলিমেন্ট তৈরি করা হয়েছে যা ব্রাউজারে প্রদর্শিত হয়েছে। আপনি নতুন নোটিশ যোগ করতে চাইলে, প্রতিটি নোটিশকে নিবন্ধন করে অ্যারেতে যুক্ত করতে পারেন। 

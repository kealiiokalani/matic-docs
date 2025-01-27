---
id: what-is-polygon
title: Polygon কী?
description: Polygon স্কেলিং সমাধান সম্পর্কে Learn
keywords:
  - docs
  - matic
  - polygon
  - blockchain
  - ethereum scaling
image: https://wiki.polygon.technology/img/polygon-wiki.png
---

[Polygon](https://polygon.technology/) হলো একটি লেয়ার 2 স্কেলিং সমাধান, যা অফ-চেইন কম্পিউটেশনের জন্য সাইডচেইন ব্যবহার করার মাধ্যমে স্কেল অর্জন করে এবং প্রুফ-অফ-স্ট্যাক (PoS) যাচাইকারীর একটি ডিসেন্ট্রালাইজড নেটওয়ার্ক।

Polygon ডিসেন্ট্রালাইজেশন, এবং বিদ্যমান ডেভেলপার কমিউনিটি ও ইকোসিস্টেমের সুবিধা গ্রহণে কোনো প্রকারের আপোস করা ছাড়াই স্কেলেবিলিটি এবং ব্যবহারযোগ্যতার সমস্যা সমাধানের জন্য সদা কাজ করে যাচ্ছে। এর লক্ষ্য হলো dApps এবং ব্যবহারকারীর ফাংশনালিটিতে স্কেলেবিলিটি এবং আরো ভালো ব্যবহারকারীর অভিজ্ঞতা প্রদান করার মাধ্যমে বিদ্যমান প্ল্যাটফর্ম উন্নত করা।

এটি পাবলিক ব্লকচেইনের জন্য একটি স্কেলিং সমাধান। Polygon PoS দ্রুত এবং সস্তা লেনদেনের পাশাপাশি বিদ্যমান সকল Ethereum উপকরণকে সমর্থন করে।

## গুরুত্বপূর্ণ ফিচার এবং হাইলাইট {#key-features-highlights}

- **স্কেলেবিলিটি**: Polygon সাইডচেইনে দ্রুত, কম-খরচে ও নিরাপদে লেনদেন করা যায়, যা মেইনচেইন এবং Ethereum-এ ফাইনালিটি অর্জন করে, কারণ Ethereum হচ্ছে সাইডচেইনটির প্রথম সমর্থিত লেয়ার 1 বেইসচেইন।
- **উচ্চ থ্রুপুট**: অভ্যন্তরীণ টেস্টনেটে একটি একক সাইডচেইনে 10,000 TPS পর্যন্ত অর্জন করেছে; অনুভূমিক স্কেলিং-এর জন্য একাধিক চেইন যোগ করা হবে।
- **ব্যবহারকারীর অভিজ্ঞতা**: মেইনচেইন থেকে Polygon চেইনে নির্ঝঞ্ঝাট UX এবং ডেভেলপারদের সারসংক্ষেপ প্রদান; নেটিভ মোবাইল অ্যাপ এবং WalletConnect সহায়তা সহ SDK।
- **নিরাপত্তা**: Polygon চেইন অপারেটরগুলো PoS সিস্টেমে নিজেরাই স্ট্যাকার হিসেবে কাজ করে।
- **পাবলিক সাইডচেইন**: Polygon সাইডচেইন পাবলিক প্রকৃতির (একক DApp চেইনগুলোর বিপরীতে), অনুমতি বিহীন সিস্টেম এবং এতে একাধিক প্রোটোকল সমর্থনের সক্ষমতা রয়েছে।

Polygon সিস্টেমটি সচেতনতার সাথে এমনভাবে তৈরি করা হয়েছে যেন তা Polygon সাইডচেইনে অবাধে স্টেট রূপান্তর সমর্থন করতে পারে, যার মধ্যে EVM-সক্রিয় রয়েছে।

## ডেলিগেটর এবং যাচাইকারীর ভূমিকা {#delegator-and-validator-roles}

আপনি Polygon নেটওয়ার্কে একজন ডেলিগেটর বা যাচাইকারী হিসেবে অংশগ্রহণ করতে পারবেন। দেখুন:

* [যাচাইকারী কে](/docs/maintain/polygon-basics/who-is-validator)
* [ডেলিগেটর কে](/docs/maintain/polygon-basics/who-is-delegator)

## আর্কিটেকচার {#architecture}

আপনার লক্ষ্য যদি যাচাইকারী হওয়া হয়ে থাকে, তবে আপনার জন্য Polygon-এর আর্কিটেকচার বোঝা খুবই গুরুত্বপূর্ণ।

আরো তথ্যের জন্য [Polygon আর্কিটেকচার](/docs/maintain/validator/architecture) দেখুন।

### উপাদান {#components}

Polygon-এর আর্কিটেকচার সম্পর্কে বিস্তারিত ধারণা পেতে মূল উপাদানগুলো দেখুন:

* [Heimdall](/docs/pos/heimdall/overview)
* [Bor](/docs/pos/bor/overview)
* [চুক্তি](/docs/pos/contracts/stakingmanager)

#### কোডবেস {#codebases}

মূল উপাদানগুলো সম্পর্কে বিস্তারিত বোঝার জন্য, নিম্নলিখিত কোডবেস দেখুন:

* [Heimdall](https://github.com/maticnetwork/heimdall)
* [Bor](https://github.com/maticnetwork/bor)
* [চুক্তি](https://github.com/maticnetwork/contracts)

## নির্দেশিকা {#how-tos}

### নোড সেটআপ {#node-setup}

আপনি যদি Polygon Mainnet বা Mumbai Testnet-এ একটি সম্পূর্ণ নোড রান করতে চান তবে আপনি অনুসরণ করতে পারেন [একটি Validator Node](/maintain/validate/run-validator.md) গাইড চালান ।

### স্ট্যাকিং-এর কার্যক্রম {#staking-operations}

যাচাইকারী এবং ডেলিগেটর প্রোফাইলের জন্য কীভাবে স্ট্যাকিং প্রক্রিয়াটি সম্পন্ন করা হয় তা দেখুন:

* [যাচাইকারী স্ট্যাকিং-এর কার্যক্রম](docs/maintain/validate/validator-staking-operations)
* [ডেলিগেট](/docs/maintain/delegate/delegate)

---
title: "Onmyoji Shikigami"
layout: "lx"
date: 2023-08-11T02:18:09+07:00
draft: false
description: "Bộ kỹ năng SSR Kujaku Myoo trong Onmyoji."
summary: "Bộ kỹ năng SSR Kujaku Myoo trong Onmyoji."  
---

<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
  }
  .container {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
    background-color: #fff;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }
  table {
    width: 100%;
    border-collapse: collapse;
  }
  th, td {
    padding: 10px;
    text-align: left;
    border-bottom: 1px solid #ddd;
  }
</style>

<div class="container">
  <h2>Employee Table</h2>
  <div>
    <select id="bloodGroupSelect">
      <option value="">Chọn nhóm máu</option>
      <option value="A">Nhóm máu A</option>
      <option value="B">Nhóm máu B</option>
      <option value="AB">Nhóm máu AB</option>
      <option value="O">Nhóm máu O</option>
    </select>
    <select id="nationalitySelect">
      <option value="">Chọn quốc tịch</option>
      <option value="Việt Nam">Việt Nam</option>
      <option value="Mỹ">Mỹ</option>
      <option value="Tây Ban Nha">Tây Ban Nha</option>
      <option value="Nhật Bản">Nhật Bản</option>
      <option value="Đức">Đức</option>
    </select>
    <select id="genderSelect">
      <option value="">Chọn giới tính</option>
      <option value="Nam">Nam</option>
      <option value="Nữ">Nữ</option>
    </select>
  </div>
  <table id="employeeTable">
    <thead>
      <tr>
        <th>Họ và Tên</th>
        <th>Nhóm Máu</th>
        <th>Quốc Tịch</th>
        <th>Giới Tính</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Nguyễn Văn A</td>
        <td>A</td>
        <td>Việt Nam</td>
        <td>Nam</td>
      </tr>
      <tr>
        <td>John Smith</td>
        <td>B</td>
        <td>Mỹ</td>
        <td>Nam</td>
      </tr>
      <tr>
        <td>Maria García</td>
        <td>O</td>
        <td>Tây Ban Nha</td>
        <td>Nữ</td>
      </tr>
      <tr>
        <td>Satoshi Tanaka</td>
        <td>AB</td>
        <td>Nhật Bản</td>
        <td>Nam</td>
      </tr>
      <tr>
        <td>Laura Müller</td>
        <td>A</td>
        <td>Đức</td>
        <td>Nữ</td>
      </tr>
    </tbody>
  </table>
</div>
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
{{< filter1 >}}


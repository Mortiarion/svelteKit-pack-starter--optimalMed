<!-- <h1>ANESTESIOLOGIST</h1> -->

<script lang="ts">
	import Breadcrumb from '$lib/components/components-pages-doctors/Bredcrumbs.svelte';
	import SectionWork from '$lib/components/components-pages-doctors/SectionWork.svelte';
	import SectionDuties from '$lib/components/components-pages-doctors/SectionDuties.svelte';
	import type { BreadcrumbData, SectionWorkData, SectionDutiesData } from '$lib/types';

	// let BreadcrumbData: BreadcrumbData = {
	// 	bredCrumbsHead: 'Головна',
	// 	bredCrumbsCategories: 'Робота анестезіологом у Польщі'
	// };
	// let SectionWorkData: SectionWorkData = {
	// 	heading: 'Робота',
	// 	subtitle: 'анестезіологом у Польщі',
	// 	paragraph1:
	// 		'У зв`язку зі складною ситуацією з медичними кадрами польські роботодавці готові приймати на роботу анестезіологом у Польщі іноземних спеціалістів, зокрема з колишніх союзних республік, гарантуючи адекватну заробітну плату та інші преференції.',
	// 	paragraph2:
	// 		'Наша компанія пропонує працевлаштування та подальшу підтримку лікарям-вихідцям з України та Білорусі. З нашою допомогою ви отримаєте можливість обирати з великої кількості вакансій з різними умовами в різних регіонах країни.'
	// };
	// let SectionDutiesData: SectionDutiesData = {
	// 	heading: 'Посадові',
	// 	subtitle: 'обов`язки анестезіолога',
	// 	paragraph:
	// 		'Повна назва цієї спеціалізації звучить як "анестезіолог-реаніматолог". Лікар цього профілю працює з усіма видами анестезії, а також займається веденням інтенсивної терапії. Таким чином, іноземні громадяни, які отримали роботу анестезіологами в Польщі:',
	// 	list1: 'ретельно вивчають історію хвороби пацієнта;',
	// 	list2:
	// 		'проводять з ним особисту бесіду, інформують про те, яку анестезію буде застосовано, в якому стані перебуватиме пацієнт і які складнощі на нього можуть очікувати під час виходу з наркозу;',
	// 	list3: 'проводять алергопроби;',
	// 	list4:
	// 		'визначаються з видом використовуваної анестезії, оцінюють ризики, підбирають препарати, прораховують дозування;',
	// 	list5: 'призначають так звану премедикацію - медикаментозну підготовку до введення анестезії;',
	// 	list6: 'перебувають поруч із пацієнтом в операційній, контролюють його стан;',
	// 	list7: 'за необхідності - проводять реанімаційні заходи;',
	// 	list8: 'спостерігають хворого в ранньому післяопераційному періоді;',
	// 	list9: 'оформляють медичну документацію.'
	// };
	export let data;
</script>

<Breadcrumb data={data.BreadcrumbData} />
<SectionWork data={data.SectionWorkData} />
<SectionDuties data={data.SectionDutiesData} />

